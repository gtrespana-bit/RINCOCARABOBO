# Adaptación de `reformat-venezuela` → web RemodelaT Coruña

> Documento de traspaso. Fuente analizada: repo público `gtrespana-bit/reformat-venezuela`
> (clonado el 2026-09-04 para este análisis). El **código** de la web de Coruña vivirá en
> un repo aparte (`remodelat-coruna-web`); aquí queda el plan de qué reutilizar y qué cambiar.

## 1. Conclusión

**Sí, reutilizar la arquitectura de `reformat-venezuela`.** Es un sitio Astro muy maduro y,
lo más importante, está construido con un patrón de **«fuente única de verdad»** (datos en
`src/data/*.ts`, componentes genéricos). Eso significa que la adaptación es **~90 % trabajo
de datos/contenido + retoque de tokens de diseño**, no reescritura de código.

## 2. Qué es `reformat-venezuela` (arquitectura)

- **Astro 6** + `viewTransitions`, sitemap con i18n, RSS, integración i18n es/en.
- **Patrón datos-desacoplados**: `src/data/brand.ts`, `routeMap.ts`, `zone-slugs.ts`,
  `city-hubs.ts`, `zone-before-after.ts`, `zone-media.ts`, `blog-slugs.ts`, `project-cases*`.
- **SEO programático local**: ~32 zonas × 3 servicios = ~96 páginas `remodelacion-<servicio>-<zona>`.
- **Componentes**: `GodHero`, `GodMarquee`, `BeforeAfter`, `MethodComparison`,
  `GuaranteeMatrix`, `FAQ`, `SEO`, `ServiceSchema`, `Breadcrumb`, `CityHub`,
  `ZoneGallery`, `ZoneAside`, `ZoneCrossLinks`, `ProjectCaseStudy`, `Lightbox`, etc.
- **Blog** en content collections (`src/content/blog/`) con versiones ES y EN.
- **Scripts de build SEO**: `check-images`, `shorten-meta`, `fix-trailing-slashes`,
  `check-seo`, `inject-image-dimensions`, `check-mobile-pwa`, `indexnow`.
- **Fuentes autoalojadas**: Cormorant Garamond (serif) + Manrope (sans) — mismas que el plan.

## 3. Qué se reutiliza TAL CUAL (sin tocar)

- Todo el esqueleto Astro, los componentes, los scripts de build/SEO, el sitemap, el RSS,
  las fuentes, la estructura de `BaseLayout` y la lógica de hreflang/canonical.
- El patrón de `brand.ts` como fuente única (cambiar UN archivo → cambia todo el sitio).

## 4. Qué se CAMBIA (tabla concreta)

| Área | Venezuela (hoy) | Coruña (destino) |
|---|---|---|
| **Marca** (`brand.ts`) | RemodelaT Venezuela · +58 422 799 7043 · contacto@remodelat.net | RemodelaT Coruña · teléfono/email ES `[PENDIENTE]` |
| **Antigüedad** | «23 años», «desde 2003», `yearsExperience: 23` | ⚠️ **QUITAR.** Es una S.L. **nueva**. Sustituir por experiencia del fundador (sin fecha de fundación de la empresa) |
| **Terminología** | remodelación, plomería, louzas, tina, condominio, junta de condominio | reforma, fontanería, sanitarios, bañera, comunidad de propietarios |
| **Moneda** | $ (USD) | € (sin IVA; IVA 10 % vs 21 % según obra) |
| **Zonas** | 32 zonas de Carabobo/Caracas | ~8-12 municipios de A Coruña (ver §6) |
| **Precios** | $1.200–9.000 baños, etc. | Bandas mercado 2026 (ver `04-finanzas/calibracion-tarifas-mercado-2026.md`): baño 5.800–6.400 €, cocina 5.000–6.000 €, integral 80 m² 29.000–32.000 €, piso 100 m² 36.000–39.000 € |
| **Colores** (`global.css` tokens) | negro cálido `#14120e` + oro `#c9a961` + crema `#faf8f4` | **navy + oro** para diferenciar (p. ej. `--ink:#10222f`; conservar el oro o variarlo levemente) |
| **Testimonios** | Personas reales de Venezuela (Gabriela, Ricardo, Laura…) | ⚠️ **NO reutilizar.** Esperar clientes reales de Coruña; mientras, dejar fuera o usar texto neutro sin nombres |
| **Fotos de obras** | Proyectos reales de Venezuela (Guataparo, Caracas…) | ⚠️ Solo como «trabajos previos del fundador» **claramente etiquetados**, o esperar obras de Coruña. No presentarlas como obras de A Coruña |
| **Idioma** | es + en | solo **es** de momento (quitar o desactivar `en/`) |
| **Piscinas** | servicio activo | `[PENDIENTE]` (decisión del plan aún abierta) |
| **Domótica** | solo ES | mantener (baja prioridad) |

## 5. Checklist de ejecución (para la conversación del repo de código)

1. Clonar `reformat-venezuela` como base (o fork privado → renombrar a `remodelat-coruna-web`).
2. `brand.ts`: nombre, teléfono, email, `areas` → «A Coruña y área metropolitana (Arteixo, Oleiros, Culleredo, Cambre…)». **Eliminar** `yearsExperience`/`FOUNDED_YEAR`/«desde 2003».
3. `global.css`: tokens de color negro→navy (y re-verificar contraste WCAG).
4. Renombrar slugs y copys: `remodelacion-*` → `reforma-*` (find/replace + renombrar archivos `.astro`).
5. `zone-slugs.ts` + `city-hubs.ts`: sustituir las 32 zonas por los municipios de A Coruña.
6. Precios a € (bandas de mercado 2026) en todas las páginas de zona y servicio.
7. Reescribir terminología venezolana (ver §4).
8. Blog: reescribir para A Coruña (empezar con 3–5 posts clave; no traducir los de Caracas/Valencia).
9. Quitar `en/` (o dejarlo para después).
10. Testimonios y fotos: sustituir por material propio (nada de nombres/fotos de clientes venezolanos).
11. `routeMap.ts`, sitemap, `ServiceSchema` (areaServed = municipios de Coruña).
12. Logo (`b_este_es_nuestro_logo.png`) y favicon.
13. Legales RGPD: aviso legal, privacidad, cookies (el formulario recoge datos).

## 6. Municipios propuestos (zona de trabajo — confirmar con Rubén)

A Coruña (ciudad) + área metropolitana: **Arteixo, Oleiros, Culleredo, Cambre, Sada,
Bergondo, Betanzos, Carral, Abegondo**. (El plan confirma: «A Coruña ciudad + área metropolitana».)

## 7. Contenido ya redactado en este repo (copiar tal cual)

Ver [`textos/`](textos/README.md): inicio, servicios, sobre-nosotros, proceso, contacto, SEO.
Cifras coherentes con el plan (D-0001…D-0004); nada inventado.

## 8. Riesgos / NO hacer

- ❌ No copiar «23 años / desde 2003» (falso para una S.L. nueva).
- ❌ No copiar testimonios ni nombres de clientes venezolanos.
- ❌ No presentar fotos de obras venezolanas como obras de A Coruña.
- ❌ No conectar el repo de negocio a Vercel (solo el repo de la web).
- ✅ Pedir permiso antes de usar fotos de casas de clientes.
