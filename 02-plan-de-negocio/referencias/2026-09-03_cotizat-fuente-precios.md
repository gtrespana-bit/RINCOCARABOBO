# CotizaT — fuente de precios y partidas (referencia para el plan)

- **Fecha del análisis:** 2026-09-03
- **Repo fuente:** `https://github.com/gtrespana-bit/generador-comercial.git`
  (CotizaT). Era privado; **Rubén lo hizo público el 2026-09-03** para poder usarlo
  como fuente del plan de negocio de A Coruña.
- **Estado:** `[VALIDO]` como fuente interna. Es un proyecto propio de Rubén
  (generador de presupuestos de construcción/remodelación).
- **Autor del uso:** Rubén + revisión con IA.

> ✅ **Ventaja clave:** los precios que contiene **no son inventados**: son datos
> investigados y referenciados por Rubén (con fuentes, fechas, min/max y confianza)
> dentro de CotizaT. Son la base perfecta para el plan financiero y para las
> plantillas de presupuesto de RemodelaT Coruña.

## 1. Qué es CotizaT

Aplicación (web + escritorio) de **presupuestos y control comercial para construcción
y remodelación**: catálogo de partidas (APU), mediciones, recursos con precios por país
y generación de PDF. Tiene cobertura para **18 países**, incluida **España** (ES):

| Dato España (en CotizaT) | Valor |
|---|---|
| País | España — código `ES` |
| Moneda | EUR |
| IVA por defecto | 21 % |
| ID fiscal | NIF |
| Glosario de traducción | `glosarios/ES.json` (136 entradas) |
| Recursos con precio nacional | 388 (`precios_recursos_espana.csv`) |
| Estado | LISTO (cierre 2026-08-25) |

## 2. Archivos útiles del repo CotizaT (para el plan)

| Archivo (en `generador-comercial`) | Contenido | Utilidad |
|---|---|---|
| `basedatos_partidas/salida/precios_recursos_espana.csv` | **388 recursos ES** en €: mano de obra, materiales y maquinaria; con precio referencia / min / max / fuente / fecha (2026-08-25) / confianza | Fuente directa de costes/tarifas para plan financiero |
| `ANALISIS_PRECIOS_ESPANA_MANO_OBRA.md` | Estudio de **mano de obra España**: convenios 2024-2026, coste empresa vs tarifa de mercado | Distinguir "coste de tener empleados" vs "tarifa de subcontrata" |
| `docs/INVESTIGACION_PRECIOS_ESPANA.md` | Investigación de precios ES (fuente citada en el CSV) | Trazabilidad de las cifras |
| `basedatos_partidas/glosarios/ES.json` | Traducción/adaptación de términos al español de España | Terminología correcta en presupuestos |
| `basedatos_partidas/datos/descompuestos/` (3.006 partidas) | Partidas descompuestas (formulas con recursos) | Cálculo de costes de obras tipo (baño, cocina, partidas) |
| `basedatos_partidas/salida/catalogo_partidas.csv/.xlsx/.json` | Catálogo completo de partidas | Consulta de partidas estándar |
| `LISTADO_ESTADO_PAISES.md` | Matriz de los 18 países (moneda, IVA, recursos) | Contexto |

## 3. Cifras clave España (extraídas 2026-09-03, fuente: `precios_recursos_espana.csv` y `ANALISIS_PRECIOS_ESPANA_MANO_OBRA.md`, fecha datos 2026-08-25)

**Mano de obra — tarifa facturada por el profesional (sin incluir cargas del empleador):**

| Oficio | €/h referencia | Rango | Jornada 8 h aprox. |
|---|---|---|---|
| Oficial 1.ª (general/albañil) | 21 | 18–25 | 144–200 €/día |
| Colocador de pisos / enchapador | 22 | 18–26 | — |
| Electricista | 24 | 20–28 | — |
| Fontanero/plomero | 23 | 19–27 | — |
| Pintor | 20 | 16–24 | — |
| Ayudante / peón | 15 | 12–18 | 96–144 €/día |

**Coste empresa (tener empleados en nómina, 2026):** oficial 1.ª ≈ **17–20 €/h** en zona
media española (19–23 en Madrid/Cataluña); peón ≈ 13–16 €/h. Fórmula usada: bruto anual
×1,3215 (SS empresa) + costes fijos. (Fuente: análisis interno CotizaT, con referencias
a convenio colectivo, Presupix, ObraHub, etc.)

> ⚠️ Distinción importante para el plan: **si RemodelaT Coruña contrata oficiales en
> nómina**, el coste es el "coste empresa"; **si subcontrata a autónomos**, la tarifa de
> mercado es la del cuadro superior (coste + beneficio del autónomo).

## 4. Cómo lo usaremos

- Fuente de **costes y tarifas** para la sección financiera y la estructura de costes de
  obras tipo (reforma de baño, cocina, integral €/m²).
- Base para las **plantillas de presupuesto** (`09-plantillas`) y la futura herramienta
  de presupuestación de la empresa.
- Los **desgloses de obra** (mediciones por m², partidas) se podrán calcular con las
  partidas descompuestas de CotizaT cuando se definan los servicios y calidades.

## 5. Reglas de uso en este repositorio

- No duplicamos la base completa de CotizaT aquí (es la fuente de verdad viva en su repo).
- Cuando se copie un extracto (tabla, CSV parcial) se indicará: **fuente, fecha y archivo
  exacto** de CotizaT.
- Es contenido propio de Rubén: uso autorizado para RemodelaT Coruña.
- Los precios de mercado pueden necesitar **ajuste a la realidad de A Coruña/Galicia**
  (contrastes con proveedores locales reales antes de usarlos en ofertas a clientes).

## Enlaces

- Repo CotizaT: https://github.com/gtrespana-bit/generador-comercial
- Datos confirmados del plan: [../datos-confirmados.md](../datos-confirmados.md)
