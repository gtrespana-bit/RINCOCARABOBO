# Tesorería de arranque — hoja mensual (dic 2026 → dic 2027)

- **Fecha:** 2026-09-03 · **Estado:** `[BORRADOR]` primera versión para validar el
  arranque mes a mes. Es una **herramienta de trabajo**: cada mes se sustituyen los
  supuestos por cifras reales (presupuestos, obra firmada, facturas, pagos).
- **Horizonte:** dic 2026 (llegada/preparación) → dic 2027 (cierre del año 1).
- **Regla de datos:** los importes marcados `[CONFIRMADO]` vienen de Rubén o de
  investigación con fuente; los marcados `[SUPUESTO]` son hipótesis para poder hacer la
  hoja y **hay que confirmarlas** (gestoría, presupuestos reales, primera obra).

## 0. Cómo usar esta hoja

1. Actualizar cada mes la columna real de su mes (obras, cobros, costes, gastos).
2. Contrastar el **saldo acumulado real** con el previsto: si va >500 € por debajo,
   revisar rampa de obra o gastos antes de que el fondo se agote.
3. Mantener el **IVA cobrado separado** en la cuenta (se liquida por trimestre, Modelo
   303): en esta hoja todo es sin IVA.
4. Los supuestos marcados se cambian en cuanto haya dato real (gestoría, seguros,
   herramientas, marketing…).

## 1. Supuestos

| Concepto | Valor | Estado | Base |
|---|---|---|---|
| Aportación inicial (caja) | 20.000 € | `[CONFIRMADO]` | Rubén |
| Vehículo SUV + compra | 10.000 € (dic-26) | `[CONFIRMADO]` | Rubén |
| Herramientas iniciales | 1.500 € (dic-26) | `[SUPUESTO]` | Rubén: "solo lo necesario" — importe real `[PENDIENTE]` |
| Constitución S.L. + trámites | 900 € (ene-27) | `[SUPUESTO]` (rango investigado 400–900 €) | referencia costes locales |
| Seguros: RC reformas + vehículo | 750 €/año (ene-27): RC 250 + vehículo 500 | RC `[CONFIRMADO]` rango 160–300; vehículo `[SUPUESTO]` | referencia costes locales |
| Gastos fijos mensuales | 560 €/mes: RETA 220 + gestoría 180 + centro (oficina virtual) 100 + software/varios 60 | `[CONFIRMADO]` los rangos; valores medios `[SUPUESTO]` | referencia costes locales |
| Marketing / captación | 150 €/mes | `[SUPUESTO]` (presupuesto marketing `[PENDIENTE]`, sección 05) | — |
| Retribución del socio | 1.900 €/mes bruto ≈ **1.600 €/mes netos** desde feb-27 | `[CONFIRMADO]` el neto; bruto según retención IRPF `[SUPUESTO]` | Rubén + gestoría |
| Obra pequeña tipo (baño/cocina media) | Venta ≈ 4.676 € sin IVA · coste directo ≈ 3.464 € · **margen ≈ 1.212 €** | `[CONFIRMADO]` por modelo | 04-finanzas/estructura-de-costes*.md |
| Empleados (2) | Su mano de obra **ya está dentro del coste directo** (tarifa de mercado CotizaT). Con coste real de plantilla el desembolso es algo menor → mejora de caja | `[SUPUESTO]` modalidad contractual a validar | ver notas §4 |

**Nota importante (empleados):** el coste directo de obra del modelo valora la mano de
obra a la **tarifa de mercado** (oficial 1.ª ~21 €/h). Si los 2 empleados se contratan
**solo por las horas de obra** (obra y tiempo determinados / jornada según carga), su
coste ya queda cubierto por el coste directo (y suele ser algo menor que la tarifa →
mejora el margen). Si se contratan **fijos a jornada completa**, hay que añadir su
sueldo mensual (~2.000–2.500 €/mes coste empresa cada uno) a los gastos fijos: con esta
rampa de obras NO cuadra → modalidad de contratación es decisión crítica a validar.

## 2. Plan de obra base (rampa confirmada: 1 obra/mes → 2–3 en paralelo)

Escenario **20 obras pequeñas en el año** (2 por mes de mar a jul y sep a dic, con
descanso de agosto; arranque 1 en feb). Cada obra ≈ 2 semanas con equipo → 2 obras/mes
en paralelo es lo que permite la capacidad confirmada (1 integral ≈ sustituye a ~4–5
pequeñas; se modelará aparte cuando se firme la primera).

## 3. Tesorería mensual (€, sin IVA)

| Mes | Obras | Cobros | Costes obra | G. fijos | Marketing | Retribución | Inversión | Saldo mes | Saldo acum. |
|---|---|---|---|---|---|---|---|---|---|
| dic-26 | 0 | 0 | 0 | 560 | 150 | 0 | 11.500 | −12.210 | 7.790 |
| ene-27 | 0 | 0 | 0 | 560 | 150 | 0 | 1.650 | −2.360 | 5.430 |
| feb-27 | 1 | 4.676 | 3.464 | 560 | 150 | 1.900 | 0 | −1.398 | 4.032 |
| mar-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 3.847 |
| abr-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 3.661 |
| may-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 3.476 |
| jun-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 3.291 |
| jul-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 3.105 |
| ago-27 | 1 | 4.676 | 3.464 | 560 | 150 | 1.900 | 0 | −1.398 | 1.708 |
| sep-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 1.522 |
| oct-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 1.337 |
| nov-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 1.151 |
| dic-27 | 2 | 9.352 | 6.927 | 560 | 150 | 1.900 | 0 | −185 | 966 |

**Totales año:** 20 obras · venta ≈ 93.520 € · margen bruto ≈ 24.246 € · **saldo final
dic-27 ≈ +966 €** (habiendo pagado toda la inversión de arranque ≈ 13.150 €).

> Simplificaciones (anotadas para no confundir): el cobro de cada obra se supone en el
> mes en que termina (en la realidad: 30–40 % señal a la firma, resto por hitos);
> materiales pagados en el mismo mes; **retenciones de garantía** (5–10 % hasta ~3 meses
> tras la entrega) NO están en la hoja → a cierre de año quedarían **≈ +1–2 k€ por
> cobrar en 2028**. La retención de IRPF de la nómina se ingresa trimestralmente (en la
> hoja se resta el bruto completo cada mes → conservador). IVA no modelado (se liquida y
> no es caja disponible).

## 4. Lectura: ¿cuadra el objetivo de 90–115 k€?

| Caso | Obras/año | Venta ≈ | Saldo final dic-27 ≈ |
|---|---|---|---|
| Prudente bajo | 18 | 84 k€ | −1.459 |
| Mínimo para no tocar fondo | 19 | 89 k€ | −246 |
| **Plan base** | **20** | **93,5 k€** | **+966** |
| Recomendado medio | 21–22 | 98–103 k€ | +2.178 a +3.391 |
| Límite alto del objetivo | 23–24 | 108–112 k€ | +4.603 a +5.815 |

Conclusiones honestas:

1. **El objetivo elegido (90–115 k€) funciona solo cerca del extremo alto o con margen
   real > 1.212 €/obra.** Con 20 obras y los supuestos medios, el año cierra con ~1 k€ de
   colchón (más retenciones por cobrar). Para un colchón cómodo: **21–23 obras** o
   mejorar el margen medio.
2. **Palancas que mejoran la caja sin inventar nada:** (a) mano de obra con plantilla
   propia a coste real < tarifa de mercado → margen real por obra mayor; (b) retenciones
   de garantía que se cobran en 2028 (+1–2 k€); (c) una **integral** aporta ≈5.760 € de
   margen por ~3 meses → 1–2 integrales al año equivalen a ~5–10 obras pequeñas y
   liberan semanas de gestión; (d) ajustar marketing/herramientas/centro a lo real.
3. **Riesgo de caja del arranque:** el mínimo de saldo se toca en feb–mar (~4 k€) y
   agosto (~1,7 k€). Si feb–mar se retrasan las primeras firmas, el fondo aguanta ~2
   meses sin obra (≈5,4 k€ ene-27).
4. **Contratación de los 2 empleados:** validar modalidad (por obra / jornada según
   carga) — con empleados fijos a jornada completa esta rampa no cierra (ver §1).

## 5. Qué falta para afinar (al llegar a A Coruña / con gestoría)

- [ ] Presupuesto real de gestoría y validación del bruto para neto 1.600 €/mes.
- [ ] Seguro del vehículo y RC con primas reales; coste real del centro (domicilio vs
      coworking).
- [ ] Importe real de herramientas y del marketing de arranque.
- [ ] Modalidad contractual de los 2 empleados (por obra vs fijos).
- [ ] Sustituir obra "media pequeña" por la mezcla real (baños/cocinas/integral) según
      presupuestos firmados.
