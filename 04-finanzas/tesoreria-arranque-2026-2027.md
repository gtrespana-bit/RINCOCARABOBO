# Tesorería de arranque — v2 con modelo de grupos de obra (dic 2026 → dic 2027)

- **Fecha:** 2026-09-03 (v2 tras corrección de Rubén sobre capacidad real) · `[BORRADOR]`
- **Corrección clave (Rubén, 2026-09-03):** la v1 asumía capacidad de "1–2 obras
  pequeñas/mes" (estructura tipo "Rubén + tarifas"), lo que **no refleja la operativa**.
  Realidad: **1 grupo (oficial + ayudante) hace 1 baño o 1 cocina por semana → hasta 4
  obras pequeñas/mes**. Con un grupo contratado, planificar 1 obra/mes = **pérdidas**
  (trabajadores parados 3 de cada 4 semanas). Esta v2 usa el modelo de grupos.
- **Regla de datos:** `[CONFIRMADO]` = Rubén o investigación con fuente; `[SUPUESTO]` =
  hipótesis a validar (marcadas). Nada inventado presentado como dato.

## 1. Estructura real de costes por obra (desglose CotizaT, 2026-09-03)

Calculado de los descompuestos de CotizaT (recurso a recurso) + productos investigados:

| Obra tipo | Coste directo (mid, s/IVA) | Mano de obra | Materiales | ≈ Semanas de grupo |
|---|---|---|---|---|
| Baño 4,5 m² | 3.543 € | **1.437 € (41 %)** | 2.105 € | ~1,1 |
| Cocina 3 m | 3.386 € | **725 € (21 %)** | 2.661 € | ~0,6 |
| Integral 80 m² | 16.450 € | **7.596 € (46 %)** | 8.854 € | ~5,8 |

> Obra pequeña media (mix 50/50 baño/cocina): venta ≈ **4.676 €** s/IVA (≈ 5.660 € c/IVA)
> · materiales ≈ **2.383 €** · **contribución por obra ≈ 2.293 €** (la contribución paga
> sueldos del grupo + estructura). Rangos de venta del modelo validado: baño 5.290–6.290 €
> c/IVA y cocina 4.485–6.575 € c/IVA.
> Coste real de grupo: 1 semana oficial+ayudante ≈ 40 h×(18,5 €/h) + 40 h×(14,5 €/h) =
> **1.320 €/semana** `[SUPUESTO]` (coste empresa medio de los rangos CotizaT 17–20 €/h
> oficial y 13–16 €/h ayudante).

## 2. Modelo de grupos (confirmado por Rubén, 2026-09-03)

1. **Grupo 1** (1 oficial + 1 ayudante): se contrata con las primeras obras; cubre
   baños, cocinas, cambios de suelo, etc. → hasta **4 obras pequeñas/mes**.
2. Cuando entra una **obra grande** (≈ 3 meses, ≈ 30.000 € `[PENDIENTE: IVA dentro o
   fuera]`): se contrata el **Grupo 2** (1 oficial + 1 ayudante), **dedicado a la obra
   grande**.
3. El **Grupo 1** sigue con las pequeñas; si alguna semana no hay pequeña, **apoya a la
   obra grande** → ésta se termina antes (más rendimiento).

## 3. Estructura de costes mensual con grupo contratado

| Concepto | €/mes | Estado |
|---|---|---|
| Grupo 1: oficial + ayudante (coste empresa) | 5.300 | `[SUPUESTO]` rango 4.800–5.700 (según convenio real gallego y horas) |
| RETA del administrador (Rubén) | 220 | rango confirmado 206–235 |
| Gestoría S.L. | 180 | rango 120–250 |
| Centro: oficina virtual/domicilio | 100 | rango 36–179 |
| Software, comunicaciones | 60 | `[SUPUESTO]` |
| Marketing / captación | 150 | `[SUPUESTO]` |
| Retribución de Rubén (bruto ≈ 1.900 = neto 1.600) | 1.900 | neto confirmado; bruto según IRPF |
| **Total estructura mensual (grupo 1 activo)** | **≈ 7.910** | |

**Equilibrio con grupo 1:** 7.910 €/mes ÷ 2.293 € de contribución por pequeña =
**≈ 3,5 obras pequeñas/mes**. Nada de "1 obra/mes": eso pierde ≈ 4.800 €/mes.

| Ritmo de pequeñas (grupo 1) | Resultado mensual | Venta anual ≈ (11 meses) |
|---|---|---|
| 3 / mes | **− 1.031 €/mes** (pierde) | 154 k€ |
| 3,5 / mes (equilibrio) | ≈ 0 | 180 k€ |
| **4 / mes (capacidad plena)** | **+ 1.262 €/mes** | 206 k€ |
| 4/mes + apoyo a obra grande en semana libre | mejora (la grande rinde antes) | — |

*(Antes de impuestos y de recuperar inversión. La venta anual de 200 k€+ con un solo
grupo de pequeñas es el escenario donde el negocio deja beneficio con margen 35 %.)*

## 4. Obra grande con Grupo 2 (≈ 30.000 €, 3 meses)

| Hipótesis de venta | Venta s/IVA | Coste ≈ | Margen ≈ | MO modelada | Semanas-grupo |
|---|---|---|---|---|---|
| "30.000 €" con IVA | 24.800 € | 18.370 € | 6.430 € | ≈ 8.480 € | 6,4 |
| "30.000 €" sin IVA | 30.000 € | 22.222 € | 7.778 € | ≈ 10.260 € | 7,8 |

> ⚠️ **Punto crítico a validar:** si el Grupo 2 está fijo 12 semanas en la obra grande a
> jornada completa, su coste sería ≈ 12 × 1.320 = 15.840 €, **por encima de la mano de
> obra que modela una integral de 80 m² (≈ 7.600–10.300 €)**. Eso significa que, o la
> obra grande real es de más superficie/alcance que el modelo de 80 m², o el Grupo 2 no
> está 12 semanas a jornada completa (apoya en pequeñas, o la obra se hace con más
> rendimiento / menos semanas). **Hay que confirmar con Rubén la obra grande real** antes
> de fijar números del Grupo 2. Hasta entonces: tratar la integral como "margen extra"
> con MO ya cubierta por el Grupo 2 y semanas de apoyo del Grupo 1.

## 5. Implicaciones (a cerrar con Rubén)

1. **Con grupos fijos, el objetivo de facturación del año 1 sube**: ≈ 3,5 obras/mes de
   media ≈ **175–205 k€ de venta anual** para cubrir estructura + dejar beneficio. El
   objetivo previo de 90–115 k€ solo valía sin grupo fijo (estructura tarifa). **Reabrir
   objetivo** con los datos reales.
2. **Contratación**: validar modalidad (fijos por obra vs. indefinidos) y convenio
   gallego real → cambia el punto de equilibrio directamente.
3. Si la demanda no llena 4 semanas/mes del grupo, las semanas libres se cubren con
   **apoyo a obra grande** o con **pequeñas de catálogo** (pintura, suelos) — por eso
   Rubén acepta "todo tipo de trabajos" pero no micro-mantenimiento.
4. La retención de garantía (5–10 % de cada obra, cobro a ~3 meses) y el IVA no están en
   estas cuentas (IVA se separa y liquida por trimestre).

## 6. Pendiente para cerrar la hoja mensual definitiva

- [ ] Confirmar: obra grande ≈ 30.000 € ¿IVA incluido o no? ¿superficie/alcance típico?
- [ ] Confirmar: modalidad de contratación de los grupos y coste real (convenio A Coruña).
- [ ] Confirmar: objetivo de facturación año 1 revisado (a la luz de §5.1).
- [ ] Rampa real: mes a mes, primeras obras y momento de contratación del Grupo 1 y del
      Grupo 2 → tabla mensual definitiva.
- [ ] Presupuestos reales: gestoría, seguros, centro, herramientas, marketing.
