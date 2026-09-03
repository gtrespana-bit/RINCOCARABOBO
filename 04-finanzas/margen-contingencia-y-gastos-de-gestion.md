# Política de margen, contingencia y gastos de gestión — RemodelaT Coruña S.L.

- **Fecha:** 2026-09-03
- **Estado:** `[BORRADOR]` — propuesta para confirmar con Rubén (las partes que son su
  decisión están marcadas). Los **hechos** (referencias sectoriales) llevan fuente y fecha.
- **Objeto:** definir cómo se convierte el **coste directo** de una obra (modelos de
  `04-finanzas`) en **precio al cliente**, y cómo se cubren los **imprevistos** y los
  **gastos de estructura** sin inventar partidas ni sorprender al cliente.

## 1. Cómo se forma el precio hoy (modelo validado)

En los pilotos de baño, cocina e integral el precio de venta se forma así:

```
Coste directo (partidas CotizaT ES + productos a precio investigado, sin IVA)
      × 1,35  (margen comercial del 35 % sobre coste; margen "tipo CotizaT")
      = Base imponible
      × 1,21  (IVA)
      = Precio al cliente
```

Ese 35 % es un **margen comercial bruto**: debe cubrir, a la vez, los **gastos de
gestión/estructura**, la **reserva de imprevistos** y el **beneficio neto** de la empresa.
Este documento reparte ese margen en tres bolsas para que las cuentas cuadren.

## 2. Referencias sectoriales (hechos, con fuente)

| Concepto | Referencia de mercado | Fuente |
|---|---|---|
| Gastos generales (GG) | En contratación pública: **13–17 % sobre el PEM** (RD 1098/2001, art. 131 RGLCAP); obra privada: sin regulación, el sector usa el 13 % como referencia | seguroconstruccion.es; Hacienda (informe Junta Consultiva 2019-040); motordepresupuestos.com (2026) |
| Beneficio industrial (BI) | En contratación pública: **6 %**; obra privada: sin regulación, 5–10 % según mercado | ídem |
| Aplicación en serie | GG se aplica sobre el PEM y BI sobre (PEM + GG): PVP ≈ PEM × 1,13 × 1,06 | motordepresupuestos.com (2026-04-18) |
| Contingencia / imprevistos | Obra residencial estándar: reservar **5–10 % del presupuesto**; rehabilitaciones con incertidumbre (tabiques, instalaciones antiguas): hasta **15–25 %** | reformasuru.com (2026-06); estudiokonzept.com (2026-01); livingbyesparza.es (2025-12) |

Traducción a % sobre el **precio de venta sin IVA** (estructura pública típica):
GG 13 % s/PEM ≈ **11 % del PVP**, BI 6 % s/subtotal ≈ **6 % del PVP** (≈17 % en total).
El margen RemodelaT del 35 % sobre coste equivale a ≈ **26 % del PVP**: queda margen para
contingencia + colchón, coherente con que la empresa es pequeña y asume riesgo de ejecución.

## 3. Propuesta de política RemodelaT (a confirmar por Rubén)

### 3.1. Margen comercial objetivo: **35 % sobre el coste directo (mínimo)**

- Mantener el 35 % usado en los pilotos como **objetivo mínimo** (base imponible = coste
  × 1,35). Es lo que hace que los precios al cliente (5.290–6.290 € baño, 4.485–6.575 €
  cocina, 307–365 €/m² integral) estén dentro del mercado 2026.
- Subir margen (40–45 %) solo en: calidades *premium*, obras pequeñas con mucho riesgo
  oculto (edificios antiguos) o cuando la validación con presupuestos reales lo
  justifique. `[PENDIENTE] validar con Rubén al primer contraste real`
- Si se ejecuta con **empleados propios** (coste empresa real 17–20 €/h < tarifa de
  mercado 21–24 €/h que usa CotizaT), el margen real mejora sin tocar el precio.

### 3.2. Reparto interno del margen (para saber si el 35 % cubre)

Desglose orientativo sobre el precio de venta sin IVA (obra pequeña tipo, punto medio):

| Concepto | % sobre coste | % sobre PVP sin IVA | Ej. baño (PVP ≈ 4.782 €) |
|---|---|---|---|
| Coste directo | 100 % | 74,1 % | ≈ 3.542 € |
| Gastos de gestión/estructura (ref. GG 13 % s/PEM) | ≈ 10–15 % | ≈ 8–11 % | ≈ 380–525 € |
| Reserva de contingencias de obra | ≈ 6–8 % | ≈ 4–6 % | ≈ 215–285 € |
| Beneficio neto antes de impuestos (resto) | ≈ 12–19 % | ≈ 9–14 % | ≈ 430–670 € |

> El **% real** de gastos de gestión se cerrará con la contabilidad del primer año
> (gestoría + centro de negocios + seguros + software + vehículo). Hasta entonces, usar
> estos rangos para no gastarse el margen: **no dar todo el 35 % como beneficio**.
> `[PENDIENTE] seguimiento con la tesorería real`.

### 3.3. Contingencia (imprevistos): reserva interna, precio cerrado

- **Propuesta (obra pequeña/media, baños y cocinas):** reserva interna de **≈ 8 % del
  presupuesto sin IVA** (dentro de la práctica habitual 5–10 %). El presupuesto al cliente
  se entrega **cerrado**: la empresa absorbe los imprevistos razonables hasta ese importe;
  por encima (o cambios pedidos por el cliente), **modificación documentada** — tal como
  ya recoge la [plantilla de presupuesto](../09-plantillas/presupuesto.md).
- En **rehabilitaciones o integrales** con instalaciones ocultas: elevar la reserva al
  10–12 % o, si la obra lo aconseja, mostrar una **partida explícita "Imprevistos"** en el
  presupuesto (transparente para el cliente). Decidir por obra. `[PENDIENTE]`
- Regla de control: la reserva no liberada al cierre de obra pasa a **beneficio/colchón**
  de la empresa (nunca a "regalar" descuentos fuera de lo pactado).
- En la tesorería se separará una **cuenta de reservas** con lo acumulado.

### 3.4. Gastos de gestión y estructura

- Cubiertos por el margen comercial (no se cobran como recargo al cliente en obra
  pequeña/media). Referencia de cuánto gastar: con **≈ 12 obras pequeñas/año**, cada obra
  debe cargar ≈ 350–450 € de estructura (≈ 8–9 % del PVP de un baño).
- En **integrales grandes** (varias semanas, más gestión, proyecto/permisos posibles) se
  valorará una línea de **gestión de obra** explícita. `[PENDIENTE]`

## 4. Números por obra tipo (puntos medios del modelo, 2026-09-03)

| Obra tipo | Coste medio | PVP ×1,35 (s/IVA) | Margen bruto 35 % | Reserva ≈ 8 % s/PVP |
|---|---|---|---|---|
| Baño 4,5 m² | ≈ 3.542 € | ≈ 4.782 € | ≈ 1.240 € | ≈ 380 € |
| Cocina 3 m | ≈ 3.385 € | ≈ 4.570 € | ≈ 1.185 € | ≈ 365 € |
| Integral 80 m² | ≈ 16.450 € | ≈ 22.210 € | ≈ 5.760 € | ≈ 1.780 € |

*(El margen de la integral es mayor pero cubre más semanas de gestión y más riesgo.)*

## 5. Punto de equilibrio mensual (costes fijos investigados — ver referencia de costes)

| Gasto fijo mensual | Rango investigado | Punto medio usado |
|---|---|---|
| Cuota RETA autónomo (tramo 1, sin ingresos aún) | 206–235 €/mes | 220 € |
| Gestoría S.L. (contabilidad + fiscal + laboral básica) | 120–250 €/mes | 180 € |
| Centro: oficina virtual/domicilio profesional (o coworking) | 36–179 €/mes | 100 € |
| Seguro RC reformas (prorrateado anual) | 160–300 €/año → 13–25 €/mes | 20 € |
| Software, comunicaciones, varios | `[PENDIENTE]` | 60 € |
| **Total gastos fijos (sin retribución del socio)** | ≈ 430–850 €/mes | **≈ 580 €/mes** |

**Equilibrio (margen medio ≈ 1.200 € por obra pequeña; ≈ 5.760 € por integral):**

| Escenario | Necesario para cubrir |
|---|---|
| Solo gastos fijos (580 €/mes) | ≈ 0,5 obra pequeña/mes, o 1 integral cada ~10 meses |
| Gastos fijos + retribución moderada (≈ 1.500 €/mes brutos) | ≈ 1,7 obras pequeñas/mes, o ≈ 0,4 integrales/mes (1 integral ≈ 2,5 meses de costes) |

> Implicación práctica: el **objetivo comercial mínimo realista es ≈ 1,5–2 obras
> pequeñas/mes de media** (con 1–2 empleados y subcontratas puntuales), o el mix con
> integrales equivalente. Esto se cierra en el objetivo de año 1 con Rubén.

## 6. Decisiones pendientes de Rubén

- [ ] Confirmar margen objetivo mínimo 35 % (y % para calidades premium / obra con riesgo).
- [ ] Confirmar política de contingencia: reserva interna 8 % y precio cerrado (3.3) frente
      a partida visible en integrales.
- [ ] Confirmar reparto interno del margen y partida de gastos de gestión.
- [ ] Retribución del socio y objetivo de facturación/obras año 1 (se cierra en
      `02-plan-de-negocio/07-plan-financiero.md` §5).

## Fuentes

- GG/BI: [seguroconstruccion.es](https://www.seguroconstruccion.es/gastos-generales-y-beneficio-industrial-de-una-obra-que-son-y-que-porcentajes-se-utilizan/) ·
  [motordepresupuestos.com](https://motordepresupuestos.com/margen-y-beneficio-industrial-construccion) (2026-04-18) ·
  RD 1098/2001 art. 131.
- Contingencia: [reformasuru.com](https://www.reformasuru.com/post/por-que-evitar-reformas-sin-presupuesto-escrito)
  (2026-06) · [estudiokonzept.com](https://estudiokonzept.com/cuanto-cuesta-una-reforma-integral/) (2026-01) ·
  [livingbyesparza.es](https://livingbyesparza.es/precio-reforma-integral/) (2025-12).
- Costes fijos (RETA, gestoría, seguros, centro de negocios): ver
  [referencia de costes locales](../02-plan-de-negocio/referencias/2026-09-03_costes-locales-gestion-espana.md).
