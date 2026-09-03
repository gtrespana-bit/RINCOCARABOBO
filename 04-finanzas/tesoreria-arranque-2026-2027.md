# Tesorería de arranque — v4: modelo de grupos + coste laboral real + tarifas recalibradas a mercado 2026 (dic 2026 → dic 2027)

- **Fecha:** 2026-09-03 (v4 tras la corrección de Rubén: precios 20–30 % bajos) ·
  `[BORRADOR]`
- **v4:** precios de venta **recalibrados a mercado 2026** (estaban 20–30 % por debajo;
  Rubén: suelo 24 €/m², demolición 15,50 €/m² como baratos). Fuentes y tabla en
  [calibracion-tarifas-mercado-2026.md](calibracion-tarifas-mercado-2026.md). Venta
  pequeña media s/IVA 4.676 → **≈ 5.900 €**; piso 100: 28.170 → **≈ 37.500 €**.
- **v1 (obsoleta):** asumía capacidad de 1–2 obras/mes y estructura "Rubén + tarifas".
- **v2 (obsoleta como método de costes):** ya usaba el modelo de grupos (hasta 4
  pequeñas/mes, Grupo 2 para obra grande), pero **estimaba el coste de los trabajadores
  con tarifas/hora de CotizaT** (18,5/14,5 €/h). CotizaT es el generador comercial:
  su propia base marca la hora de oficial a 21 € como *"tarifa facturada, no incluye
  cargas del empleador"* → no sirve como coste interno.
- **v3:** coste laboral calculado desde **salario de convenio de la construcción de
  A Coruña 2026 + Seguridad Social patronal 2026** (detalle y fuentes en
  [coste-laboral-real-empleados-2026.md](coste-laboral-real-empleados-2026.md)).
- **Regla de datos:** `[CONFIRMADO]` = Rubén o investigación con fuente · `[SUPUESTO]` =
  hipótesis marcada · nada inventado presentado como dato.

## 1. Coste real de un empleado (A Coruña, convenio construcción 2026 + SS)

| Perfil | Bruto/mes (14 pagas) | Bruto/año | SS empresa 2026 | **Coste/año** | **Coste/mes** | €/h productiva |
|---|---|---|---|---|---|---|
| **Ayudante** (Nivel X) | 1.557 € | 21.795 € | ≈ 33,0–37,35 % | 28.991–29.940 € | **2.416–2.495 €** | 16,6–17,1 |
| **Oficial 1ª** (Nivel VIII) | 1.632 € | 22.848 € | ≈ 33,0–37,35 % | 30.388–31.382 € | **2.532–2.615 €** | 17,3–17,9 |
| **Grupo (1+1)** | — | — | — | 59.379–61.321 € | **4.948–5.110 €** (medio 5.030) | ~34–35 €/h dúo |

- SS empresa 2026: 23,60 % CC + 5,50 % desempleo + 0,20 % FOGASA + 0,60 % FP + 0,75 % MEI
  ≈ 30,65 %, más AT/EP **2,35 %** (CNAE 43) o **6,70 %** (CNAE 41/construcción general).
- **Semana de grupo** (40 h oficial + 40 h ayudante): **≈ 1.356–1.400 €**.
- `[PENDIENTE]`: confirmar CNAE (gestoría), jornada exacta y pluses del convenio con la
  primera nómina.

## 2. Horas y coste de obra (horas reales de los descompuestos de CotizaT)

De CotizaT solo se usan los **rendimientos (horas)** — la medición de oficio real de
Rubén — nunca sus precios:

| Obra tipo | Horas (of.+ay.) | Coste MO real | Materiales (s/IVA) | Coste directo real | **Venta s/IVA (mercado 2026)** | Margen s/coste real |
|---|---|---|---|---|---|---|
| Baño 4,5 m² | 75,8 | **1.286–1.328 €** | 2.105 € | 3.391–3.433 € | **5.800–6.400 €** (≈ 6.100) | **≈ 78–88 %** |
| Cocina 3 m | 38,0 | **647–668 €** | 2.661 € | 3.308–3.329 € | **5.000–6.000 €** (≈ 5.500) | **≈ 65–80 %** |
| Piso 100 m² (A) | 519 | **8.804–9.092 €** | 11.022 € | 19.826–20.114 € | **36.000–39.000 €** (≈ 37.500) | **≈ 85 %** |
| Integral 80 m² | 324,9 | **5.506–5.686 €** | 8.854 € | 14.360–14.540 € | **29.000–32.000 €** | **≈ 105–120 %** |

> - **Recalibrado a mercado 2026**: la venta sube de 4.676 € a ≈ 5.900 € s/IVA de media
>   (materiales 2.383 €) → **contribución por pequeña ≈ 3.500 €**. El margen real alto
>   (la MO propia a convenio cuesta menos que la tarifa de mercado que paga el cliente)
>   es legítimo y explica el 40–45 % que Rubén ve en CotizaT y más con plantilla propia.
> - Pequeña media: venta ≈ **5.900 €** s/IVA (≈ 6.500 € c/IVA con IVA 10 % en vivienda
>   habitual) · **contribución ≈ 3.500 €/obra**. Detalle de la recalibración en
>   [calibracion-tarifas-mercado-2026.md](calibracion-tarifas-mercado-2026.md).

## 3. Modelo de grupos (confirmado por Rubén, 2026-09-03)

1. **Grupo 1** (oficial + ayudante) desde las primeras obras: baños, cocinas, suelos →
   hasta **4 obras pequeñas/mes**.
2. Cuando entra una **obra grande** se contrata el **Grupo 2**, dedicado a ella. La obra
   grande real de Rubén: **piso ~100 m²** (suelo nuevo, 2 baños, cocina, puertas…) →
   costeada en [su ficha](estructura-de-costes-reforma-piso-100.md): venta recalibrada a
   mercado **≈ 37.500 € s/IVA (≈ 41.000 € c/IVA al 10 %)**, ≈ 6,5 semanas-grupo de
   trabajo directo.
3. El Grupo 1 sigue con las pequeñas y **apoya a la obra grande** las semanas sin
   pequeñas → la grande avanza sin coste extra de MO (ya pagada) y termina antes.

## 4. Estructura mensual con el Grupo 1 activo

| Concepto | €/mes | Estado |
|---|---|---|
| Grupo 1 (coste empresa, convenio + SS 2026) | **5.030** (4.948–5.110) | tabla de convenio + SS; CNAE a fijar |
| RETA del administrador (Rubén) | 220 | rango 206–235 |
| Gestoría S.L. | 180 | rango 120–250 |
| Centro: oficina virtual/domicilio | 100 | rango 36–179 |
| Software, comunicaciones | 60 | `[SUPUESTO]` |
| Marketing / captación | 150 | `[SUPUESTO]` |
| Retribución de Rubén (bruto ≈ 1.900 ≈ neto 1.600) | 1.900 | neto confirmado |
| **Total estructura (Grupo 1 activo)** | **≈ 7.640** | |

**Equilibrio (recalibrado):** 7.640 €/mes ÷ ≈ 3.500 € de contribución por pequeña =
**≈ 2,2 obras pequeñas/mes** (antes 3,3 con los precios viejos). Con grupo contratado y
1 sola obra/mes se pierde ≈ 4.100 €/mes (grupo parado), por eso las puertas de
contratación por cartera (§7–8).

| Ritmo de pequeñas (Grupo 1) | Resultado mensual | Venta anual ≈ (11 meses) |
|---|---|---|
| 2 / mes | ≈ − 600 €/mes (− 6 k€/año) | ≈ 130 k€ |
| ≈ 2,2 / mes (equilibrio) | ≈ 0 | ≈ 143 k€ |
| 3 / mes | **+ 2.911 €/mes** (+ 32 k€/año) | ≈ 195 k€ |
| **4 / mes (capacidad plena)** | **+ 6.428 €/mes** (+ 77 k€/año) | ≈ 260 k€ |
| 4/mes + apoyo a obra grande en semana libre | mejora (la grande rinde antes) | — |

*(Antes de impuestos y de recuperar inversión; con retención de garantía, IVA y un mes de
vacaciones por ajustar en la tabla mensual definitiva.)*

### 4.1. Mes 6 operativo (julio 2027, 4 obras pequeñas) — actualizado a precios de mercado

Mes 6 = 6.º mes operando (feb–jul 2027, grupo a plena carga), con la venta recalibrada:

| Concepto | €/mes | Detalle |
|---|---|---|
| Ventas 4 obras pequeñas (s/IVA) | 23.600 | 4 × 5.900 € (≈ 26.000 € c/IVA al 10 % en vivienda) |
| − Materiales de las 4 obras | − 9.532 | 4 × 2.383 € (precio de tienda s/IVA) |
| − Estructura del mes (§4) | − 7.640 | grupo 5.030 + retribución 1.900 + 710 |
| **= Beneficio real del mes (antes de impuestos)** | **+ 6.428** | ≈ 27 % s/venta |
| − Impuesto de Sociedades (15–25 % nueva S.L.) | | quedan ≈ 5.000–5.500 € en la empresa |

> **Dos niveles de margen (no confundir):**
> - **Margen de obra ≈ 55–70 % sobre coste directo real** (con plantilla propia a
>   convenio, la MO cuesta menos que la tarifa de mercado que paga el cliente).
> - **Beneficio neto del mes ≈ 27 % s/venta**: después de sueldos, retribución de Rubén,
>   gestoría y marketing. Rubén validó el *formato* de este ejemplo cuando el resultado
>   era +1.532 €; con la recalibración de mercado el mismo mes pasa a **+6.428 €**.
> - **Caja ≠ beneficio**: cobros por hitos 50/20/20/10 y garantía final a ~3 meses.
> - Sensibilidad: 3 pequeñas → **≈ + 2.900 €**; con precio antiguo 3 pequeñas era −761 €:
>   la recalibración hace que incluso un mes a 3 obras sea positivo.

## 5. Obra grande real (piso ~100 m²) con Grupo 2

**Escenario real descrito por Rubén (2026-09-03):** piso de 100 m² — suelo de cerámica
nuevo en todo, **2 baños**, **cocina**, **puertas incluidas**, etc. Costeado en
[estructura-de-costes-reforma-piso-100.md](estructura-de-costes-reforma-piso-100.md):

| Concepto | Valor |
|---|---|
| Coste directo real (MO convenio + materiales) | ≈ 19.826–20.114 € |
| **Venta al cliente (mercado 2026, recalibrada)** | **≈ 37.500 € s/IVA → ≈ 41.000 € c/IVA** (IVA 10 %; ≈ 410 €/m²; rango 36.000–39.000 s/IVA / 40.000–43.000 c/IVA) |
| Margen real sobre coste | ≈ 85 % (coste directo); neto de Grupo 2 ≈ + 11.400 €/obra |
| Trabajo directo | 519 h → **6,5 semanas-grupo** (≈ 32 días-grupo) |
| Si va a cargo del Grupo 2 (fijo 12 sem ≈ 960 h) | ocupa ≈ 54 % de su jornada teórica |

**Portfolio de obra grande (variantes, según Rubén 2026-09-03):** la típica es la de
arriba **sin ventanas ni calefacción**; algunas obras añaden **ventanas** (≈ +2.500–3.000 €
s/IVA → ≈ 43.000–46.000 € c/IVA) o **suelo radiante + aerotermia** (≈ +12.000–23.500 €
c/IVA instalados → ≈ 52.000–66.500 € c/IVA), y otras son **chalets/viviendas
independientes de 200 m²+** (≈ 65.000–78.000 € c/IVA observados por Rubén, ≈ 12–15
semanas-grupo → con Grupo 2 dedicado ~3–4 meses). Detalle y fuentes en la
[§6 de la ficha](estructura-de-costes-reforma-piso-100.md).

> ⚠️ **Lectura para el Grupo 2:** la obra típica (A) **no consume 12 semanas a jornada
> completa de un grupo**: son ≈ 6,5 semanas de trabajo directo, que con gestión, compras
> y remates dan 2–3 meses de calendario. Las 12 semanas del Grupo 2 dedicado solo se
> justifican con las **variantes grandes (D: chalet 200 m²+)**, con varias obras
> encadenadas, o si ese grupo **apoya también otras obras** en los huecos. Confirmar con
> Rubén el alcance real de cada obra al ofertar; la grande sirve como "margen extra
> ≈ 11.400 € netos por obra" con la MO ya cubierta por el grupo.

## 6. Implicaciones (a cerrar con Rubén)

1. **El modelo correcto evita las pérdidas estructurales**: los grupos solo se activan
   con cartera firmada (§7–8). Con esa regla y los precios recalibrados, el **caso tipo
   del año 1 deja ≈ +77.400 €** antes de impuestos y **la caja nunca baja de ≈ 7.000 €**
   con los 20.000 € de capital.
2. **Contratación**: coste ya calculado (convenio + SS); falta fijar modalidad. El modelo
   encaja con **Grupo 2 por obra determinada** (se activa y renueva con cada grande) y
   Grupo 1 indefinido u obra según prefiera Rubén → a confirmar con la gestoría.
3. Semanas libres del Grupo 1: apoyo a obra grande o pequeñas de catálogo (pintura,
   suelos) — por eso el alcance no se limita a baños/cocinas (pero no micro-mantenimiento).
4. Garantía del 10 % e IVA no modelados mes a mes: los absorbe el colchón de caja
   (mínimo ≈ 7.000 € en el caso tipo); prever liquidez para la primera liquidación
   trimestral de IVA.

## 7. Caso tipo del año 1, mes a mes (reglas de Rubén + precios de mercado 2026)

**La secuencia operativa (2026-09-03):**
- **dic-26 / ene-27:** constitución, compras (vehículo 10.000 + herramientas 1.500 +
  constitución 900 + seguros 750) y **campaña de captación** (sin grupo).
- **feb-27:** se firma la 1.ª obra pequeña → **se agenda y la ejecuta Rubén** (coste del
  mes ≈ 2.610 €: retribución + fijos). No se contrata a nadie.
- **mar-27:** hay **3 obras cerradas** → se **contrata el Grupo 1**.
- **abr-27:** Grupo 1 a plena carga (4 pequeñas).
- **may-27:** se firma el **piso 100 m²** → **Grupo 2** (por obra) y la grande (may–jul).
- **ago-27:** termina la grande → **fin de contrato del Grupo 2** (nadie parado).
- **sep–nov-27:** 2.ª obra grande cerrada en verano → se re-contrata el Grupo 2.
- **dic-27:** termina la 2.ª grande; Grupo 1 cierra el año.

**Números recalibrados a mercado 2026** (devengo, sin IVA): pequeña media venta 5.900 €
(mat. 2.383 → **contribución ≈ 3.500 €**); piso 100: 37.500 € s/IVA (mat. 11.022 → bruto
26.478, devengado en 3 meses); estructura = fijos 710 + retribución 1.900 + grupo 5.030.

| Mes | Peq. | Grupo 1 | Grupo 2 | Venta s/IVA | Materiales | Estructura | Resultado | Caja acum. |
|---|---|---|---|---|---|---|---|---|
| feb-27 | 1 | — | — | 5.900 | −2.383 | −2.610 | **+907** | 7.047 |
| mar-27 | 3 | G1 | — | 17.700 | −7.149 | −7.640 | **+2.911** | 9.958 |
| abr-27 | 4 | G1 | — | 23.600 | −9.532 | −7.640 | **+6.428** | 16.386 |
| may-27 | 4 | G1 | G2 (grande #1) | 36.100 | −13.206 | −12.670 | **+10.224** | 26.610 |
| jun-27 | 4 | G1 | G2 (grande #1) | 36.100 | −13.206 | −12.670 | **+10.224** | 36.834 |
| jul-27 | 4 | G1 | G2 (grande #1) | 36.100 | −13.206 | −12.670 | **+10.224** | 47.058 |
| ago-27 | 3 | G1 | — | 17.700 | −7.149 | −7.640 | **+2.911** | 49.969 |
| sep-27 | 4 | G1 | G2 (grande #2) | 36.100 | −13.206 | −12.670 | **+10.224** | 60.193 |
| oct-27 | 4 | G1 | G2 (grande #2) | 36.100 | −13.206 | −12.670 | **+10.224** | 70.417 |
| nov-27 | 4 | G1 | G2 (grande #2) | 36.100 | −13.206 | −12.670 | **+10.224** | 80.641 |
| dic-27 | 3 | G1 | — | 17.700 | −7.149 | −7.640 | **+2.911** | 83.552 |

**Totales:** **38 obras pequeñas + 2 pisos 100 m² en cadena → venta ≈ 299.200 € s/IVA
(≈ 329.000 € c/IVA al 10 %) · resultado ≈ + 77.400 € antes de impuestos · caja siempre
positiva (mín ≈ 7.000 € en feb; final ≈ 83.500 €).**

> Notas: resultado = devengo (la grande se cobra 50/20/20/10). IVA al 10 % en vivienda
> habitual (a confirmar con gestoría) y 10 % de garantía de cada obra no restados mes a
> mes: los absorbe el colchón (caja mínima ≈ 7.000 €). El resultado es **sensible a la
> captación**: ≈ +3.500 € por pequeña y ≈ +26.500 € por grande; si se ejecutan menos
> obras, baja en proporción.

## 8. Régimen objetivo, sensibilidad y la palanca real (recalibrado a mercado)

**Unidad económica (precios de mercado 2026):**

| Acción | Efecto |
|---|---|
| + 1 obra pequeña/mes (grupo ya activo) | **+ 3.500 €/mes** |
| + 1 obra grande (piso 100) con Grupo 2 dedicado 3 meses | **+ 11.400 € netos por obra** (26.478 de margen − 15.090 de coste del G2) |
| Grupo 2 con 1 pequeña/mes extra en huecos | + 3.500 €/mes adicionales |
| **Régimen objetivo (2 grupos en cadena)** | **≈ + 10.000 €/mes** de media cuando ambos rinden |

**Escenarios de año 1 (misma lógica de puertas):**

| Caso | Pequeñas | Grandes | Venta s/IVA | Resultado ≈ |
|---|---|---|---|---|
| Cauteloso (arranque más lento) | ~28 | 1 | ≈ 205 k€ | ≈ + 45.000 € |
| **Caso tipo (objetivo)** | 38 | 2 en cadena | ≈ 299 k€ | ≈ + 77.000 € |
| Con una grande adelantada / chalet | 38 | 2 + chalet | ≈ 380 k€+ | ≈ + 100.000 €+ |

> **Conclusiones:**
> 1. **El precio de venta era la palanca escondida**: al recalibrar a mercado (+20–30 %),
>    cada obra aporta mucho más y el año 1 pasa de ≈ +12.000 € a ≈ +77.000 € con el mismo
>    volumen y estructura (Rubén: los presupuestos estaban "20–30 % por debajo de mercado").
> 2. **El límite real sigue siendo la captación**, pero con precios correctos el margen de
>    error es enorme: aunque la demanda del año 1 sea la mitad del caso tipo, el negocio
>    ya es claramente rentable.
> 3. `[PENDIENTE]` validar los PVP propuestos (§ [calibracion](calibracion-tarifas-mercado-2026.md))
>    y el IVA aplicable (10 % vs 21 %) con la gestoría antes de la primera oferta real.

## 9. Pendiente para cerrar la hoja mensual definitiva

- [ ] **Validar PVP recalibrados** ([calibracion-tarifas-mercado-2026.md](calibracion-tarifas-mercado-2026.md)):
      baño ≈ 5.800–6.400 s/IVA, cocina ≈ 5.000–6.000, piso 100 ≈ 36.000–39.000 → subir los
      presupuestos tipo antes de la primera oferta.
- [ ] **Confirmar tipo de IVA** con la gestoría (reforma vivienda habitual: 10 % vs 21 %).
- [ ] Confirmar **modalidad de contratación** de los grupos (G1 indefinido u obra; G2 por
      obra) y CNAE (AT/EP 2,35 % vs 6,70 %), jornada y pluses del convenio.
- [ ] Obra grande real: al ofertar, identificar la **variante (A–D de la
      [ficha](estructura-de-costes-reforma-piso-100.md))** y costear con medición real.
- [ ] Pedir 2–3 presupuestos reales de gremios en A Coruña (solador, electricista,
      fontanero, carpintero) para calibrar el resto de partidas.
- [ ] Descuentos reales de proveedor de materiales (hoy: precio de tienda sin IVA).
- [ ] Presupuestos reales: gestoría, seguros, centro, herramientas, marketing.
- [ ] Convertir este caso tipo en **seguimiento mensual real** (previsto vs. ejecutado).
