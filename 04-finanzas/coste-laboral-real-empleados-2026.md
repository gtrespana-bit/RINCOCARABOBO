# Coste laboral real de empleados — convenio construcción A Coruña + Seguridad Social 2026

- **Fecha:** 2026-09-03 · `[BORRADOR]` — método nuevo por indicación de Rubén.
- **Corrección de método (Rubén, 2026-09-03):** el coste de los trabajadores **no se
  calcula con las tarifas por hora de CotizaT**, porque CotizaT es el **generador
  comercial** (precios de venta), no una fuente de costes internos. La propia base de
  CotizaT lo declara: sus horas de mano de obra son *"tarifa facturada, no incluye
  automáticamente cargas del empleador"* (columna `observaciones` de
  `precios_recursos_espana.csv`). El coste real se calcula desde el **salario de convenio
  + Seguridad Social a cargo de la empresa**, por mes y por año.
- **Regla de datos:** `[CONFIRMADO]` con fuente · `[PENDIENTE]` = a validar con gestoría /
  nómina real. Nada inventado.

## 1. Salario de convenio — Construcción y Obras Públicas de A Coruña (tablas 2026)

| Perfil | Nivel | Bruto/mes | Bruto/año (14 pagas) | Neto estimado/mes (IRPF Galicia, soltero) |
|---|---|---|---|---|
| **Ayudante de oficio** | X | 1.557 € | 21.798 € | ≈ 1.280 € |
| **Oficial de 1ª** | VIII | 1.632 € | 22.848 € | ≈ 1.334 € |

Fuentes: tablas del convenio provincial de construcción de A Coruña 2026 publicadas en
[calculadornomina.es/convenios/construccion/a-coruna](https://calculadornomina.es/convenios/construccion/a-coruna/)
(cifras de peón ordinario 1.519 €/mes y oficial 1ª 1.632 €/mes cruzadas con el agregador
CCOO del mismo convenio). `[PENDIENTE]`: confirmar contra el texto oficial del convenio
(pluses de asistencia/transporte, antigüedad y pagas no incluidos arriba).

## 2. Seguridad Social a cargo de la empresa (2026)

| Concepto | Tipo empresa | Notas |
|---|---|---|
| Contingencias comunes | 23,60 % | 2026 |
| Desempleo (contrato indefinido) | 5,50 % | 6,70 % si temporal |
| FOGASA | 0,20 % | |
| Formación profesional | 0,60 % | |
| MEI | ≈ 0,75 % | Mecanismo de Equidad Intergeneracional |
| **Subtotal sin AT/EP** | **≈ 30,65 %** | |
| Accidentes de trabajo/EP | **2,35 %** (CNAE 43, construcción especializada) **o 6,70 %** (CNAE 41 / Cuadro II tipo d, personal de oficios en obras) | Depende del encuadre que asigne la gestoría |

Fuentes: tipos 2026 en workrono.com, factorial.es y BOE (Orden PJC/297/2026, bases y
tipos); tarifa de primas AT/EP 2026 (gestoriapastor.org, tarifa DA 61.ª LGSS): CNAE 41 =
IT 3,35 + IMS 3,35 = **6,70 %**; CNAE 43 (excepto 436) = 1,20 + 1,15 = **2,35 %**.
`[PENDIENTE]`: fijar CNAE real de la sociedad con la gestoría (reformas → habitualmente
CNAE 43 o 41 según cómo se encuadre la actividad).

## 3. Coste real para la empresa (bruto × 1 + SS empresa)

Jornada de referencia del sector: **1.752 h/año** `[PENDIENTE: jornada exacta del convenio]`.

| Perfil | Coste/año (sin AT/EP) | Coste/año (CNAE 43) | Coste/año (CNAE 41) | €/mes (caso 43) | €/mes (caso 41) | €/h productiva (43 → 41) |
|---|---|---|---|---|---|---|
| **Ayudante** | 28.479 € | 28.991 € | 29.940 € | 2.416 € | 2.495 € | 16,55 → 17,09 |
| **Oficial 1ª** | 29.851 € | 30.388 € | 31.382 € | 2.532 € | 2.615 € | 17,34 → 17,91 |
| **Grupo (1+1)** | 58.330 € | 59.379 € | 61.321 € | **4.948 €** | **5.110 €** | — |

- **Grupo de obra completo ≈ 4.950–5.110 €/mes** (punto medio ≈ **5.030 €/mes**; anual
  ≈ 59.400–61.300 €). Hora de trabajo del dúo ≈ 33,9–35,0 €/h → **semana de grupo
  (40 h oficial + 40 h ayudante) ≈ 1.356–1.400 €**.
- Cálculo: bruto anual (14 pagas) × (1,3065 + AT/EP); mes = /12; hora productiva = /1.752.
- Los salarios de convenio coruñeses están muy comprimidos: el ayudante cuesta casi lo
  mismo por hora que el oficial 1ª (16,6–17,1 vs 17,3–17,9 €/h) → la estructura de costes
  por obra casi no depende de mezclar perfiles.

## 4. Mano de obra real por obra tipo (horas de los descompuestos de CotizaT)

De CotizaT solo se toman los **rendimientos (horas)** de los descompuestos — la medición
de horas de oficio reales de Rubén — nunca sus precios. Horas extraídas (recurso a
recurso, distinguiendo oficial/ayudante):

| Obra tipo | Horas oficial | Horas ayudante | Total h | Días de grupo (16 h/día) | Semanas de grupo |
|---|---|---|---|---|---|
| Baño 4,5 m² (30 partidas) | 38,1 | 37,8 | 75,8 | 4,7 | ≈ 1 (0,95) |
| Cocina 3 m (20 partidas) | 22,4 | 15,6 | 38,0 | 2,4 | ≈ 0,5 |
| Integral 80 m² (comunes + bloques) | 162,3 | 162,6 | 324,9 | 20,3 | ≈ 4,1 |

> Coherente con Rubén: **1 baño ≈ 1 semana de grupo; 1 cocina ≈ media semana** (pueden
> salir 2 cocinas por semana).

**Coste de MO real por obra** (horas × coste/h real de §3) frente al coste que salía con
la tarifa CotizaT:

| Obra tipo | MO tarifa CotizaT (referencia comercial) | **MO real (convenio + SS)** | Materiales (investigados, s/IVA) | Coste directo real | **PVP mercado 2026 s/IVA** | **Margen s/coste real** |
|---|---|---|---|---|---|---|
| Baño | 1.437 € | **1.286–1.328 €** | 2.105 € | 3.391–3.433 € | **5.800–6.400 €** (≈ 6.100) | **≈ 78–88 %** |
| Cocina | 725 € | **647–668 €** | 2.661 € | 3.308–3.329 € | **5.000–6.000 €** (≈ 5.500) | **≈ 65–80 %** |
| Integral | 7.596 € | **5.506–5.686 €** | 8.854 € | 14.360–14.540 € | **29.000–32.000 €** | **≈ 105–120 %** |
| Piso 100 m² (A) | — | **8.804–9.092 €** | 11.022 € | 19.826–20.114 € | **36.000–39.000 €** (≈ 37.500) | **≈ 85 %** |

> El PVP ya no sale del modelo de costes × 1,35 (quedaba 20–30 % bajo de mercado; Rubén,
> 2026-09-03): se fija en la **banda de mercado 2026** del producto completo
> ([calibracion-tarifas-mercado-2026.md](calibracion-tarifas-mercado-2026.md)). Con
> plantilla propia a convenio el coste directo real es menor que la tarifa de mercado que
> paga el cliente, y ese diferencial es el margen real (≈ 80–90 % en pequeñas, más en la
> integral por su alcance básico sin ventanas/tabiques/calefacción). Materiales a precio
> de tienda sin IVA; con descuento de proveedor el margen real sube.

## 5. Uso en el modelo financiero

1. **Estructura mensual con Grupo 1 activo** (ver `tesoreria-arranque-2026-2027.md` v4):
   grupo **≈ 5.030 €/mes** (4.950–5.110) + 1.210 € (RETA 220 + gestoría 180 + centro 100 +
   software 60 + marketing 650) + retribución de Rubén ≈ 1.900 €/mes bruto ≈ **8.140 €/mes**.
2. **Nunca** usar la hora de CotizaT (21 €/h oficial, tarifa facturada) como coste
   interno: solo como referencia de precio de venta de MO si algún día se subcontratase
   (no es el plan).
3. `[PENDIENTE]` al contratar: nómina real (convenio oficial + pluses), CNAE/AT-EP con la
   gestoría y descuentos de proveedor de materiales → recalibrar esta ficha.
