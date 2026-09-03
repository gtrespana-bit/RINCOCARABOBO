# Inventario: web RemodelaT Venezuela (material de referencia)

- **Fecha:** 2026-09-03
- **Fuente:** repositorio `gtrespana-bit/reformat-venezuela` (GitHub)
  — web desplegada en `remodelat.net` (Vercel).
- **Autor del análisis:** Rubén (revisado con IA)
- **Estado:** `[VALIDO]` como referencia interna. Documento vivo: ampliar/actualizar.
- **Uso previsto:** fuente de información sobre la empresa y su método para el plan de
  negocio de RemodelaT Coruña y para la futura web de A Coruña.

> ⚠️ **Naturaleza del contenido:** la web venezolana adaptó ubicaciones a Venezuela
> (San Diego, Valencia, Carabobo, Caracas…) para resultar creíble en ese mercado, pero los
> **proyectos mostrados son reales y fueron ejecutados realmente en España** por Rubén.
> Cualquier dato que se reutilice para Coruña debe **devolverse a su contexto real español**.

---

## 1. Qué es el repositorio fuente

| Aspecto | Dato |
|---|---|
| Nombre | RemodelaT Venezuela |
| Tecnología | **Astro** (estático), tipografías Cormorant Garamond + Manrope, PWA (sw.js), sitemap i18n |
| Idiomas | Español (principal) + Inglés (`/en/`) |
| Despliegue | Vercel (`remodelat.net`) |
| Contacto en web | WhatsApp `+58 422 799 7043`, email `contacto@remodelat.net` |
| Estructura | Home, Sobre nosotros, Método, Servicios (12+), Proyectos (7 casos reales), Blog (47 artículos ES/EN), páginas por zona/urbanización, contacto, legal |

La web es de **nivel de calidad muy alto** (SEO, rendimiento, PWA, galerías de proyectos,
antes/después, schema, etc.). Es el **mejor modelo de referencia** para la futura web de Coruña.

## 2. Marca y posicionamiento (la "filosofía" que describe a Rubén)

- **RemodelaT** = marca creada por Rubén; en Venezuela opera como "RemodelaT Venezuela".
  La nueva empresa en A Coruña está prevista como **RemodelaT Coruña** (misma familia de marca).
- Posicionamiento declarado: **remodelaciones residenciales de alto estándar** —
  *"no competimos por ser la opción más económica, competimos por hacerlo bien"*.
- Cliente objetivo: propietarios que valoran método técnico, materiales especificados,
  supervisión, acabados de lujo y **garantía por escrito**.
- Narrativa de origen (texto de "Sobre nosotros"): *"RemodelaT nació en España… Más de 23 años
  de trayectoria en remodelaciones. Adaptamos técnicas avanzadas de construcción europea"*.
  → **Para Coruña esta narrativa vuelve a su origen natural: empresa española.**

## 3. Método (10 etapas) — contenido directamente reutilizable

1. Diagnóstico técnico real (medidas, instalaciones, humedades, soportes, accesos, logística).
2. Definición de alcance (incluido vs. no incluido, partidas y prioridades).
3. Especificación de materiales (cada material según soporte, uso, formato y exposición).
4. Presupuesto por partidas (demolición, instalaciones, impermeabilización, revestimientos…).
5. Planificación de obra (compras, permisos, protección, escombros, cronograma).
6. Protección del inmueble (pisos, ascensores, pasillos, zonas no intervenidas).
7. Ejecución supervisada (replanteos, plomos, niveles, pendientes, cortes, encuentros, sellados).
8. Pruebas antes de cerrar (tuberías, desagües, impermeabilización, puntos eléctricos).
9. Control de acabados (juntas, siliconas, esquinas, rodapiés, grifería, iluminación).
10. Entrega documentada (revisión conjunta, remates, limpieza, garantía por partidas).

**Garantía por partidas** (matriz garantía/cobertura/evidencia) — componente diferenciador clave.

## 4. Proyectos reales (7 casos de estudio en la web)

> Realizados en España; en la web venezolana se renombraron las ubicaciones.
> Para Coruña: recuperar la ubicación/contexto real con Rubén antes de usarlos.

| Caso (slug web) | Tipo | Contenido técnico destacado | Duración declarada | Fotos |
|---|---|---|---|---|
| `cocina-lujo-guataparo` | Cocina reubicada | Cocina cerrada → zona día; acceso condenado bloque 20 cm; suelo **epóxico blanco** continuo; estante flotante LED; equipos Siemens + solar térmica | 2,5 semanas | 16 |
| `cocina-caracas-quinta` | Reforma cocina | Demolición cerámica, eléctrico con cable ignífugo, revestimiento rectificado, MDF lacado + PVC termoformado, encimera cuarzo | 1 semana | 11 |
| `bano-las-mercedes-pequeno` | Baño compacto | Tabique mal posicionado → demolición y nuevo tabique ladrillo, porcelanato 30×90 rectificado, plato ROCA, mampara | 2 semanas | 14 |
| `bano-caracas` | Baño + aseo adaptado | Fontanería **multicapa PEX-Al-PEX**, porcelanato español 60×60, armario → aseo accesible, puerta corredera | 2 semanas | 13 |
| `bano-la-trigalena` | Baño townhouse | Demolición tabiques divisorios para ganar amplitud, multicapa, porcelanato 60×120, sanitarios TEKA | 1 semana | 12 |
| `bano-san-diego` | Baño poceta flotante | Albañilería ladrillo rasillón, poceta flotante TEKA, porcelanato 120×60/60×60 beige | 1 semana | 7-8 |
| `banos-quinta-la-lagunita` | Baño de lujo | División en 2 salas, ventanal rotura térmica, piedra volcánica, microcemento, porcelanato metro | 2,5 semanas | 28 |

**Materiales/equipos que se repiten (señas de calidad):** porcelanato gran formato rectificado,
multicapa PEX-Al-PEX, impermeabilización previa, TEKA/ROCA/Siemens, microcemento, epoxi,
mamparas, grifería premium, LED oculto, carpintería a medida.

## 5. Imágenes disponibles (en el repo venezolano)

- `public/images/proyectos/<caso>/` — fotos reales por proyecto (antes/obra/resultado).
- Copias originales en carpetas raíz: `Cocina Lujo Guataparo/`, `reforma baño pequeño Las Mercedes/`,
  `remodelacion comprimido/` (varios baños).
- `public/images/` — galería genérica (cocinas, baños, suelos, electricidad, domótica…) + variantes
  de tamaño (400/600/800/1600) + poster/vídeo hero (`public/videos/hero-*.mp4`).
- `marketing/facebook/…/export/` — piezas publicitarias terminadas (ver §7).

## 6. Blog (47 artículos ES/EN) — mapa de temas

- Guías de precios por servicio (reforma cocina/baño/integral, fontanería, electricidad,
  pintura por m², pisos, revestimientos).
- Guías técnicas: porcelanato vs. cerámica, microcemento vs. pintura, cómo detectar fugas,
  cuándo reinstalar eléctrico, tendencias de cocinas.
- Proceso/compras: errores en presupuestos, plazos de reforma integral, elegir empresa,
  permisos en comunidad/condominio.
- Antes/después y casos reales.

→ **Patrón claro:** "artículo de zona + artículo de precio + artículo de guía técnica".
Este mismo esquema de contenidos se replicará para Coruña con datos gallegos (precios €/m²,
normativa española, barrios de A Coruña…).

## 7. Marketing (Facebook/Instagram) — 4 colecciones en el repo fuente

| Tanda | Estilo | Piezas |
|---|---|---|
| Base | Marca azul marino/dorado | 6 flyers (captación, baños, antes/después…) |
| 2 · Premium | Editorial, tipografías oficiales | 8 piezas + hooks |
| 3 · Agencia | Dirección de arte multicapa | 6 piezas (portfolio, catálogo servicios, caso real…) |
| 4 · Élite | 4 universos visuales (Swiss White, Obsidian&Bronze, Mediterranean, Cinema) | 12 piezas + reels animados + locución |

Incluye guías de copywriting y textos para publicaciones → reutilizable como **banco de ideas**
para el marketing de Coruña (cambiando mercado, precios y datos de contacto).

## 8. Identidad visual de la marca RemodelaT

- Paleta: tinta `#14120e`, hueso `#faf8f4`, dorado `#c9a961`, blanco; acabados sobrios y de lujo.
- Tipografías: **Cormorant Garamond** (títulos, serif editorial) + **Manrope** (texto, sans).
- Estilo: secciones de gran formato, "eyebrow" en mayúsculas, marquesinas, comparativas,
  números grandes, fotografía real de obra.
- Logo actual: `b_este_es_nuestro_logo.png` en la raíz del repo venezolano.

## 9. SEO / técnica (lecciones para la web de Coruña)

- **Landings por zona**: ~35 urbanizaciones/zonas × 3 servicios (baño/cocina/integral) × 2 idiomas,
  generadas por scripts (`scripts/generate-zone-landings*.mjs`). Patrón: página general de la zona
  + páginas de servicio-por-zona con fotos, antes/después y textos locales.
- Sitemap con prioridades, breadcrumbs, crosslinks entre zonas, hreflang ES/EN.
- Scripts de calidad: chequeo de SEO, imágenes (alt, dimensiones), PWA móvil, meta cortas.
- PWA + offline, fuentes self-hosted, webp con srcset, service worker.

## 10. Qué reutilizar para Coruña vs. qué cambiar

| Elemento | ¿Reutilizable? | Notas |
|---|---|---|
| Método (10 etapas) + garantía por partidas | ✅ Sí | Núcleo del mensaje; idéntico en España |
| Narrativa "experiencia europea/española" | ✅ Sí | En Coruña es el mercado de origen: aún más creíble |
| Casos de obra (fotos + textos técnicos) | ⚠️ Con adaptación | Devolver a su contexto real español; ubicaciones y monedas a corregir |
| Fichas de proyecto / galerías antes-después | ✅ Estructura sí | Modelo de presentación excelente |
| Posicionamiento "alto estándar, no low-cost" | ✅ Sí | Diferenciador válido en A Coruña |
| Blog: esquema de temas y estructura | ✅ Sí | Reescribir con precios y normativa española (€/m², IVA, CTE) |
| Precios/costes ($ o Bs) | ❌ No | Reescribir en € con datos de mercado gallego |
| Contacto, WhatsApp +58, dominio remodelat.net | ❌ No | Datos de Coruña nuevos |
| "23 años / desde 2003 / 500+ proyectos en España" | ⚠️ Validar | Confirmar cifras reales y verificables para usarlas en Coruña |
| Landing pages por zona | ✅ Patrón sí | Adaptar a barrios de A Coruña (Los Mallos, Ensanche, Ciudad Vieja, Monte Alto… urbanizaciones del área) |
| Paleta/tipografías/estética | ⚠️ Decidir | ¿Continuidad de marca RemodelaT o identidad nueva? Decisión de marca pendiente |

## 11. Pendientes que esto abre (para el plan de Coruña)

- [ ] Confirmar con Rubén: cifras de experiencia verificables (años, n.º proyectos reales).
- [ ] Reconstruir el "mapa real" de cada proyecto (ubicación en España, año, cliente genérico)
      como archivo interno (`06-obras-y-proyectos` o aquí en referencias).
- [ ] Decidir identidad: ¿RemodelaT Coruña hereda el logo/paleta de RemodelaT o se crea nueva?
- [ ] Cuando toque la web: partir de esta base Astro (o clonarla) en lugar de empezar de cero.

## Enlaces

- Repo fuente: https://github.com/gtrespana-bit/reformat-venezuela
- Web: https://remodelat.net (Venezuela)
- Reglas de carpetas del proyecto: [README principal](../../README.md)
