# Tesorería de arranque — v3: modelo de grupos + coste laboral real (dic 2026 → dic 2027)

- **Fecha:** 2026-09-03 (v3 tras la corrección de Rubén sobre el coste laboral) ·
  `[BORRADOR]`
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

| Obra tipo | Horas (of.+ay.) | Días de grupo | Coste MO real | Materiales (s/IVA) | Coste directo real | Venta s/IVA | Margen s/coste |
|---|---|---|---|---|---|---|---|
| Baño 4,5 m² | 75,8 | 4,7 (≈ 1 sem) | **1.286–1.328 €** | 2.105 € | 3.391–3.433 € | 4.782 € | **39–41 %** |
| Cocina 3 m | 38,0 | 2,4 (≈ ½ sem) | **647–668 €** | 2.661 € | 3.308–3.329 € | 4.570 € | **37–38 %** |
| Integral 80 m² | 324,9 | 20,3 (≈ 4,1 sem) | **5.506–5.686 €** | 8.854 € | 14.360–14.540 € | 22.210 € | **53–55 %** |

> - El margen de las obras pequeñas (≈ 38–41 %) coincide con lo que Rubén observa en sus
>   presupuestos CotizaT (**40–45 % de margen real sobre costes**). Los materiales se
>   valoran a precio de tienda sin IVA; el descuento de proveedor lo subiría.
> - Obra pequeña media (mix baño/cocina): venta ≈ **4.676 €** s/IVA · materiales ≈
>   **2.383 €** · **contribución ≈ 2.293 €/obra** (la contribución paga sueldos del grupo
>   + estructura).

## 3. Modelo de grupos (confirmado por Rubén, 2026-09-03)

1. **Grupo 1** (oficial + ayudante) desde las primeras obras: baños, cocinas, suelos →
   hasta **4 obras pequeñas/mes**.
2. Cuando entra una **obra grande** se contrata el **Grupo 2**, dedicado a ella. La obra
   grande real de Rubén: **piso ~100 m²** (suelo nuevo, 2 baños, cocina, puertas…) →
   costeada en [su ficha](estructura-de-costes-reforma-piso-100.md): venta ≈ 34.090 €
   c/IVA, ≈ 6,5 semanas-grupo de trabajo directo.
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

**Equilibrio:** 7.640 €/mes ÷ 2.293 € de contribución por pequeña = **≈ 3,3 obras
pequeñas/mes**. Con grupo contratado, 1 obra/mes pierde ≈ 5.300 €/mes (grupo parado).

| Ritmo de pequeñas (Grupo 1) | Resultado mensual | Venta anual ≈ (11 meses) |
|---|---|---|
| 3 / mes | **− 761 €/mes** (− 8 k€/año) | 154 k€ |
| ≈ 3,3 / mes (equilibrio) | ≈ 0 | ≈ 171 k€ |
| **4 / mes (capacidad plena)** | **+ 1.532 €/mes** (+ 17 k€/año) | 206 k€ |
| 4/mes + apoyo a obra grande en semana libre | mejora (la grande rinde antes) | — |

*(Antes de impuestos y de recuperar inversión; con retención de garantía, IVA y un mes de
vacaciones por ajustar en la tabla mensual definitiva.)*

### 4.1. Ejemplo validado por Rubén — mes 6 operativo (julio 2027, 4 obras pequeñas)

Mes 6 = 6.º mes operando (feb–jul 2027, grupo ya a plena carga):

| Concepto | €/mes | Detalle |
|---|---|---|
| Ventas 4 obras pequeñas (s/IVA) | 18.704 | 4 × 4.676 € (≈ 22.630 € c/IVA facturados) |
| − Materiales de las 4 obras | − 9.532 | 4 × 2.383 € (precio de tienda s/IVA) |
| − Estructura del mes (§4) | − 7.640 | grupo 5.030 + retribución 1.900 + 710 |
| **= Beneficio real del mes (antes de impuestos)** | **+ 1.532** | ≈ 8 % s/venta |
| − Impuesto de Sociedades (15–25 % nueva S.L.) | | quedan ≈ 1.150–1.300 € en la empresa |

> **Dos niveles de margen (no confundir):**
> - **Margen de obra ≈ 40–45 %** (Rubén, CotizaT): margen de cada obra sobre su **coste
>   directo** (materiales + horas) — antes de estructura.
> - **Beneficio neto del mes ≈ 8 % s/venta**: después de restar sueldos, retribución de
>   Rubén, gestoría y marketing. La retribución (1.600 € netos/mes) ya está dentro de los
>   gastos; el +1.532 € es lo que queda en la empresa.
> - **Caja ≠ beneficio**: el mes 6 cobra obras de abril–mayo (pagos a 30–60 días y 5 % de
>   garantía a ~3 meses) → la tesorería va por detrás del beneficio contable.
> - Sensibilidad del mismo mes: 3 pequeñas → **− 761 €**; 2 pequeñas → **− 3.054 €**.
>   El grupo parado a medias es lo que hace perder dinero (por eso captación continua).

## 5. Obra grande real (piso ~100 m²) con Grupo 2

**Escenario real descrito por Rubén (2026-09-03):** piso de 100 m² — suelo de cerámica
nuevo en todo, **2 baños**, **cocina**, **puertas incluidas**, etc. Costeado en
[estructura-de-costes-reforma-piso-100.md](estructura-de-costes-reforma-piso-100.md):

| Concepto | Valor |
|---|---|
| Coste directo real (MO convenio + materiales) | ≈ 19.826–20.114 € |
| **Venta al cliente** (coste tarifa ×1,35 + IVA) | **≈ 34.090 € c/IVA** (≈ 341 €/m²; rango 33.100–38.400) |
| Margen real sobre coste | ≈ 40–42 % |
| Trabajo directo | 519 h → **6,5 semanas-grupo** (≈ 32 días-grupo) |
| Si va a cargo del Grupo 2 (fijo 12 sem ≈ 960 h) | ocupa ≈ 54 % de su jornada teórica |

**Portfolio de obra grande (variantes, según Rubén 2026-09-03):** la típica es la de
arriba **sin ventanas ni calefacción**; algunas obras añaden **ventanas** (≈ +2.900 €
c/IVA → ≈ 37.000 €) o **suelo radiante + aerotermia** (≈ +12.000–23.500 € → ≈ 46.000–
57.600 €), y otras son **chalets/viviendas independientes de 200 m²+** (≈ 65.000–78.000 €
c/IVA, ≈ 12–15 semanas-grupo → con Grupo 2 dedicado ~3–4 meses). Detalle y fuentes en la
[§6 de la ficha](estructura-de-costes-reforma-piso-100.md).

> ⚠️ **Lectura para el Grupo 2:** la obra típica (A) **no consume 12 semanas a jornada
> completa de un grupo**: son ≈ 6,5 semanas de trabajo directo, que con gestión, compras
> y remates dan 2–3 meses de calendario. Las 12 semanas del Grupo 2 dedicado solo se
> justifican con las **variantes grandes (D: chalet 200 m²+)**, con varias obras
> encadenadas, o si ese grupo **apoya también otras obras** en los huecos. Confirmar con
> Rubén el alcance real de cada obra al ofertar; la grande sirve como "margen extra
> ≈ 40–42 %" con la MO ya cubierta por el grupo.

## 6. Implicaciones (a cerrar con Rubén)

1. **Con grupos fijos el objetivo sube**: equilibrio ≈ 3,3 pequeñas/mes → **≈ 170 k€/año**;
   a plena carga (4/mes) **≈ 206 k€/año** y beneficio ≈ +17 k€/año. El objetivo previo de
   90–115 k€ solo valía sin grupo fijo. **Reabrir objetivo**.
2. **Contratación**: el coste de convenio ya está calculado (ficha de coste laboral);
   falta fijar modalidad (indefinido vs. obra determinada), CNAE/AT-EP y pluses → la
   gestoría lo cuadra con la primera nómina.
3. Semanas libres del Grupo 1: apoyo a obra grande o pequeñas de catálogo (pintura,
   suelos) — por eso el alcance no se limita a baños/cocinas (pero no micro-mantenimiento).
4. Retención de garantía (5–10 % cobrada a ~3 meses) e IVA: fuera de estas cuentas
   (IVA se liquida por trimestre).

## 7. Tabla mensual de tesorería (escenarios de caja, dic-26 → dic-27)

**Datos de Rubén (2026-09-03):** cobro de las obras por hitos **50 % entrada + 20 % +
20 % + 10 % final**; rampa realista de pequeñas **2–3/mes en abr–jun** (arranque
feb–mar más lento). Construido con: pequeña media 4.676 € s/IVA (materiales 2.383 €),
piso 100 m² ≈ 28.170 € s/IVA (materiales ≈ 11.022 €), estructura Grupo 1 ≈ 7.640 €/mes
(5.030 + 710 + 1.900), aportación 20.000 € con inversión dic-26 ≈ 12.400 € (vehículo
10.000 + herramientas 1.500 + constitución 900) y ene-27 seguros 750 €. Cifras **sin
IVA** (IVA se liquida por trimestre). Pequeñas cobradas dentro del mes (obra ≤ 1 semana).

**Escenario de referencia — B · moderada + 1 piso 100 m² (entra en may):**

| Mes | Peq. | Venta s/IVA | Materiales | Estructura | Grupo 2 | Cobros grande | Resultado | Caja acum. |
|---|---|---|---|---|---|---|---|---|
| dic-26 | 0 | — | — | 710 | — | — | −710 | 6.890 |
| ene-27 | 0 | — | — | 1.460 | — | — | −1.460 | 5.430 |
| feb-27 | 1 | 4.676 | −2.383 | −2.610 | — | — | −317 | 5.113 |
| mar-27 | 2 | 9.352 | −4.766 | −7.640 | — | — | −3.054 | 2.059 |
| abr-27 | 2 | 9.352 | −4.766 | −7.640 | — | — | −3.054 | −995 |
| may-27 | 3 | 14.028 | −7.149 | −7.640 | −5.030 | +14.085 (50 %) | +579 | −416 |
| jun-27 | 3 | 14.028 | −7.149 | −7.640 | −5.030 | +5.634 (20 %) | −3.464 | −3.880 |
| jul-27 | 3 | 14.028 | −7.149 | −7.640 | −5.030 | +5.634 (20 %) | −157 | −4.037 |
| ago-27 | 2 | 9.352 | −4.766 | −7.640 | — | +2.817 (10 %) | −237 | −4.274 |
| sep-27 | 4 | 18.704 | −9.532 | −7.640 | — | — | +1.532 | −2.742 |
| oct-27 | 4 | 18.704 | −9.532 | −7.640 | — | — | +1.532 | −1.210 |
| nov-27 | 4 | 18.704 | −9.532 | −7.640 | — | — | +1.532 | +322 |
| dic-27 | 4 | 18.704 | −9.532 | −7.640 | — | — | +1.532 | +1.854 |

**Venta del año ≈ 177.800 € s/IVA (≈ 215.100 € c/IVA) · 32 pequeñas + 1 piso 100.**

### Comparativa de escenarios

| Escenario | Pequeñas/año | Venta s/IVA | Caja mínima | Saldo final | Colchón extra sobre 20.000 € |
|---|---|---|---|---|---|
| A · Moderada, sin grande | 32 | 149.600 € | **− 6.332 €** (ago) | − 204 € | ≈ 6.300 € |
| **B · Moderada + piso 100 (may)** | 32 | 177.800 € | **− 4.274 €** (ago) | + 1.854 € | ≈ 4.300 € |
| C · Fuerte (4/mes desde may), sin grande | 36 | 168.300 € | + 1.298 € (abr) | + 8.968 € | 0 |
| D · Fuerte + piso 100 (sep) | 36 | 196.500 € | + 1.298 € (abr) | **+ 11.026 €** | 0 |

### Lectura (importante)

1. **Con la rampa moderada que describes (2–3/mes hasta jun), 20.000 € NO alcanzan**:
   la caja toca fondo en **agosto (−4.300 a −6.300 €)**, por el verano flojo + grupo
   pagado. Opciones: ampliar aportación a **≈ 25–26.000 €**, o **financiar el vehículo**
   (deja esos ~7–10 k€ como colchón), o anticipar el ritmo de 4/mes.
2. **Las obras grandes arreglan la caja** (entrada del 50 % ≈ 14.000 € al firmar) además
   del resultado: con 1 piso 100 el año cierra en positivo (+1.854 €) y el colchón
   necesario baja a ≈ 4.300 €.
3. **El Grupo 2 solo se contrata al firmar la obra grande** y solo se llena del todo con
   la variante D (chalet) o combinando grande + pequeñas; con un piso 100 a media jornada
   le quedan huecos (≈ 54 % de ocupación) → usar esos huecos en pequeñas/apoyo.
4. Objetivo coherente con la tabla: **≈ 36 obras pequeñas-equivalentes + 1–2 obras
   grandes → venta ≈ 190–200 k€ s/IVA (≈ 230–240 k€ c/IVA)**; por debajo (solo pequeñas
   a ritmo moderado) el año 1 roza el equilibrio con el colchón justo.

## 8. Pendiente para cerrar la hoja mensual definitiva

- [ ] Elegir (Rubén): **ritmo objetivo** (moderado 2–3/mes vs fuerte 4/mes desde may) y
      **cómo se cubre el colchón** (ampliar aportación a ≈ 26 k€ vs financiar el
      vehículo vs ritmo fuerte).
- [ ] Obra grande real: al ofertar, identificar la **variante (A–D de la [ficha](../../04-finanzas/estructura-de-costes-reforma-piso-100.md))** y costear con medición real; cerrar con Rubén cómo presupuestar suelo radiante/aerotermia (proveedor instalador habilitado).
- [ ] Modalidad de contratación de los grupos (indefinido vs. obra) y confirmación con
      gestoría de CNAE (AT/EP 2,35 % vs 6,70 %), jornada y pluses del convenio.
- [ ] Descuentos reales de proveedor de materiales (hoy: precio de tienda sin IVA).
- [ ] Objetivo de facturación año 1: cerrar con la tabla (§7): ≈ 36 pequeñas-equivalentes
      + 1–2 grandes ≈ 190–200 k€ s/IVA.
- [ ] Presupuestos reales: gestoría, seguros, centro, herramientas, marketing.
- [ ] IVA: prever liquidez de la primera liquidación trimestral (colchón extra ~5–10 %).
