# Brief para el desarrollo de la web (traspaso a repo de código)

> Este documento resume todo lo que la web necesita. **El código vivirá en un repo aparte**
> (`remodelat-coruna-web`); este repo guarda el contenido y la estrategia (el «qué decir»).
> La nueva conversación de Arena (con acceso al repo de código) puede copiar directamente
> los borradores de `textos/`.

## 1. Qué es

Web corporativa de **RemodelaT Coruña** — reformas y remodelación de viviendas en A Coruña.
Objetivo principal: **generar contactos/presupuestos** (no solo escaparate).

## 2. Sitemap propuesto

1. **Inicio** — propuesta de valor + CTA → `web-inicio.md`
2. **Servicios** — integral, cocina, baño, obra grande, accesibilidad + complementarios → `web-servicios.md`
3. **Proceso de trabajo** — método en 10 etapas + garantía → `web-proceso-de-trabajo.md`
4. **Sobre nosotros** — empresa + fundador → `web-sobre-nosotros.md`
5. **Proyectos / Portfolio** — fotos antes/después (pendiente de material)
6. **Contacto / Pedir presupuesto** — formulario + datos → `web-contacto.md`
7. **Legales** — aviso legal, privacidad, cookies (obligatorio RGPD)

## 3. Decidido (no reabrir)

- Marca de trabajo: **RemodelaT Coruña** (D-0001).
- Posicionamiento: **«reforma documentada»** — método técnico + garantía por partidas.
- Frase: «No competimos por ser la opción más económica. Competimos por hacerlo bien.»
- **Sin subcontratación** (plantilla propia).
- **No** comunidades de propietarios (D-0004) · **No** mantenimiento/micro-arreglos.
- Zona: A Coruña + área metropolitana (Arteixo, Oleiros, Culleredo, Cambre).
- Precios orientativos (s/IVA, mercado 2026) en `web-servicios.md`.

## 4. Pendiente antes de publicar (necesita a Rubén)

- [ ] **Identidad visual y dominio** (decisión A4): ¿heredar marca RemodelaT o crear? dominio `.es`.
- [ ] **Logotipo** y paleta.
- [ ] **Teléfono / email** reales.
- [ ] **Fotos reales** de obras (con permiso del cliente) — hoy no hay material público.
- [ ] Completar datos del fundador (`web-sobre-nosotros.md`).
- [ ] Decidir si se publican los **precios orientativos**.
- [ ] Validar denominación «RemodelaT Coruña S.L.» (gestoría).

## 5. Recomendación técnica

- **Astro** — y **reutilizar la arquitectura de `reformat-venezuela`** (repo público).
  Plan detallado de qué copiar y qué cambiar: [`adaptacion-reformat-venezuela.md`](../adaptacion-reformat-venezuela.md).
- Despliegue: **Vercel** (raíz del repo de la web; NUNCA conectar este repo de negocio).
- SEO: schema `LocalBusiness`, meta únicos, Google Business (ver `web-seo.md`).

## 6. Estética

Premium, sobria y de confianza. Referencias visuales: paleta navy + dorado del plan de negocio
(no obligatorio, pero coherente). Tipografía serif para titulares + sans para cuerpo.
Mucho antes/después, poco texto.
