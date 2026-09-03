# Estructura de costes — Piloto: obra tipo "reforma integral de baño estándar" (4,5 m²)

- **Fecha:** 2026-09-03
- **Estado:** `[BORRADOR]` — modelo piloto para validar el método de costes.
  Pendiente de validar con proveedores locales de A Coruña y con presupuestos reales.
- ⚠️ **PVP recalibrado a mercado 2026** (Rubén 2026-09-03: los presupuestos estaban
  20–30 % por debajo de mercado): propuesta **5.800–6.400 € s/IVA ≈ 6.400–7.000 € c/IVA
  (10 %)** para el baño completo 4–6 m² (mercado 2026: 5.000–8.000 € c/IVA; detalle y
  fuentes en [calibracion-tarifas-mercado-2026.md](calibracion-tarifas-mercado-2026.md)).
- La **mano de obra de las partidas** está a tarifa comercial CotizaT (generador de
  presupuestos). El **coste real de la MO en nómina** (convenio A Coruña 2026 + SS) y los
  márgenes reales resultantes están en
  [coste-laboral-real-empleados-2026.md](coste-laboral-real-empleados-2026.md): baño →
  MO real ≈ 1.286–1.328 € (75,8 h de grupo) → margen real ≈ 78–88 % sobre coste directo.
- **Método:** partidas descompuestas de **CotizaT** (`generador-comercial`, repo propio de
  Rubén) valoradas con los **recursos de España en €** de
  `basedatos_partidas/salida/precios_recursos_espana.csv` (fecha datos: 2026-08-25,
  fuente de cada precio indicada en el CSV). Cálculo reproducible: coste partida =
  Σ(precio recurso ES × rendimiento del recurso en la partida).
- **Moneda:** €, **sin IVA**. IVA aplicable: **10 %** en reforma de vivienda habitual
  (> 2 años) o 21 % — confirmar con gestoría.
- **Política:** ningún dato inventado. Los costes salen de la fuente CotizaT; los
  **productos finales** (porcelanato, sanitarios…) están `[PENDIENTE]` de presupuestar.

## 1. Alcance y supuestos del escenario

Baño tipo de vivienda en España (piso): **~4,5 m² útiles** (aprox. 1,8 × 2,5 m, altura 2,5 m),
**reforma integral a calidades estándar**, sin redistribución de tabiques ni cambios
estructurales, con **ducha** (plato + mampara fija).

| Supuesto de medición | Valor | Nota |
|---|---|---|
| Superficie de suelo | 4,5 m² | Supuesto de escenario |
| Alicatado de paredes (picado y nuevo) | 17 m² | Supuesto: cerramiento alicatado (~perímetro × alto) |
| Zona de ducha impermeabilizada en muro | 3 m² | Supuesto (1 ducha) |
| Puntos de agua y desagüe nuevos | 3 ud | Inodoro, lavabo, ducha |
| Tubería de agua (PPR 20) | 6 m | Supuesto de escenario |
| Tubería de desagüe 2" | 3 m | Supuesto de escenario |
| Puntos eléctricos (interruptor/toma) | 3 ud | Renovación parcial |
| Luminarias LED empotradas | 2 ud | Instalación |
| Escombro generado | 0,8 m³ | Supuesto de escenario |
| Mampara fija ducha | 1,8 m² | Supuesto (aprox. 0,9 × 2,0 m) |

> ⚠️ Los supuestos de medición son del escenario tipo y deben ajustarse a cada obra real
> (medición en visita). Los **precios unitarios** son reales (fuente CotizaT ES).

## 2. Partidas y coste directo (CotizaT ES, €)

| Código | Partida (resumen) | Un. | Cant. | Coste unit. € | Subtotal € |
|---|---|---|---|---|---|
| 02.07.03.020 | Desmontaje de aparato sanitario y su grifería | ud | 2 | 13,67 | 27,34 |
| 02.11.01.010 | Desmontaje de mueble de baño y accesorios | ud | 1 | 19,46 | 19,46 |
| 02.10.02.010 | Picado de enchapado cerámico en pared | m² | 17 | 14,48 | 246,24 |
| 02.10.01.010 | Demolición de piso cerámico y su capa de pega | m² | 4,5 | 11,02 | 49,61 |
| 12.01.01.040 | Regularización de paramento con mortero | m² | 5 | 27,23 | 136,17 |
| 10.05.01.010 | Impermeabilización de piso de baño | m² | 4,5 | 25,23 | 113,55 |
| 10.05.01.060 | Impermeabilización de muro de ducha | m² | 3 | 22,12 | 66,37 |
| 12.05.01.010 | Nivelación con mortero autonivelante (5 mm) | m² | 4,5 | 10,94 | 49,22 |
| 12.03.01.010 | Enchapado de pared con cerámica/porcelanato en capa fina | m² | 17 | 20,14 | 342,38 |
| 12.05.03.080 | Piso de porcelanato rectificado en capa fina | m² | 4,5 | 20,23 | 91,05 |
| 09.01.02.010 | Punto de agua fría/caliente para aparato | ud | 3 | 63,58 | 190,73 |
| 09.01.01.010 | Tubería de agua PPR 20 empotrada (c/roza y resane) | m | 6 | 14,02 | 84,12 |
| 09.01.03.020 | Llave de escuadra para aparato | ud | 3 | 21,24 | 63,71 |
| 09.02.02.010 | Punto de desagüe para aparato sanitario | ud | 3 | 53,88 | 161,64 |
| 09.02.01.050 | Tubería de desagüe de 2" | m | 3 | 8,34 | 25,03 |
| 09.01.04.010 | Instalación de inodoro (conexiones) | ud | 1 | 51,18 | 51,18 |
| 09.01.04.020 | Instalación de lavamanos (c/grifería y desagüe) | ud | 1 | 66,40 | 66,40 |
| 09.01.04.030 | Instalación de ducha (c/grifería) | ud | 1 | 43,35 | 43,35 |
| 09.03.07.010 | Punto de interruptor/tomacorriente (c/caja y mecanismo) | ud | 3 | 13,47 | 40,42 |
| 09.03.06.020 | Reubicación de punto eléctrico existente | ud | 1 | 49,50 | 49,50 |
| 09.04.01.060 | Instalación de luminaria LED empotrada | ud | 2 | 23,08 | 46,17 |
| 12.10.01.030 | Pintura de cielo raso, dos manos | m² | 4,5 | 8,04 | 36,20 |
| 07.07.01.020 | Mampara de baño fija de vidrio templado (instalada) | m² | 1,8 | 160,78 | 289,40 |
| 15.03.01.050 | Saco big-bag de escombro | ud | 2 | 5,21 | 10,42 |
| 15.04.01.020 | Transporte de escombro a vertedero autorizado | m³ | 0,8 | 11,50 | 9,20 |
| 15.04.01.030 | Canon de vertido de escombro mezclado | m³ | 0,8 | 7,75 | 6,20 |
| 15.07.01.030 | Limpieza final de obra para entrega | m² | 4,5 | 1,84 | 8,28 |
| 15.07.01.050 | Limpieza de aparatos sanitarios y grifería | ud | 1 | 2,33 | 2,33 |
| 16.03.01.020 | Prueba de estanqueidad de baño/ducha | ud | 1 | 16,50 | 16,50 |
| 16.04.01.050 | Prueba de presión de la red de agua | glb | 1 | 19,53 | 19,53 |

### Totales del escenario (partidas CotizaT, sin productos)

| Concepto | € |
|---|---|
| **Coste directo de partidas** (materiales básicos + mano de obra a tarifa ES + maquinaria) | **≈ 2.362 €** |
| *Precio de venta orientativo con margen 35 % (margen tipo CotizaT)* | *≈ 3.188 € — **no usar como PVP**:* |
| | *con el coste real de MO (nómina) el margen 35 % a tarifa ES queda 20–30 % bajo de mercado* |

> Notas de interpretación:
> - La mano de obra está valorada con las **tarifas de mercado ES** de CotizaT (oficial
>   1.ª ~21–24 €/h, ayudante ~15 €/h), que son precios de venta de mercado, no coste de
>   plantilla: con **empleados propios a convenio** el coste empresa real es menor
>   (17–20 €/h) → el margen real es mayor que el 35 % tipo CotizaT.
> - Por eso el **PVP no se calcula sobre la tarifa CotizaT** sino sobre la banda de
>   mercado 2026 del producto completo (§4 y ficha de calibración).

## 3. Productos finales (investigación de precios reales, 2026-09-03)

> Estas partidas de CotizaT **no incluyen el producto final**. Para completar el coste sin
> inventar, se han investigado precios reales en tiendas de bricolaje/materiales en España
> (**Obramat** —precios sin IVA, B2B— y **Leroy Merlin** —P.V.P. con IVA—) con su fuente y
> fecha. Los precios Leroy Merlin se muestran con IVA y su equivalente aproximado sin IVA
> (÷1,21) para sumarlos a las partidas (que se valoran sin IVA).

| Producto | Cant. (c/merma) | P.V.P. referencia (fuente) | ≈ sin IVA | Fuente (consultado 2026-09-03) |
|---|---|---|---|---|
| Azulejo pared baño 30×90 (pasta blanca) | ~19 m² | 9,77–14,24 €/m² sin IVA | 9,77–14,24 | Obramat, azulejos baño (blanco mate 11,50 €/m² c/IVA ≈ 9,50) |
| Porcelanato suelo (rectificado) | ~5 m² | 10,13–17,79 €/m² sin IVA | 10,13–17,79 | Obramat, suelo porcelánico interior/imitación madera |
| Inodoro + cisterna (Roca Meridian) | 1 | 265–418 € c/IVA | 219–345 | Leroy Merlin, inodoro Roca Meridian / Pack WC 417,99 € |
| Plato de ducha (acrílico 80–90 cm) | 1 | 135–270 € c/IVA | 112–223 | Leroy Merlin, platos de ducha Roca (ofertas 134,90; acrílico 169) |
| Mueble de baño con lavabo (60–80 cm) | 1 | 199–280 € c/IVA | 164–231 | Leroy Merlin, muebles baño pequeño (Espacio/Comoro 199–279) |
| Grifo lavabo monomando | 1 | 21–70 € c/IVA | 17–58 | Leroy Merlin, grifos lavabo (básico 20,79; Roca Alpine 69,99) |
| Columna de ducha monomando | 1 | 80–180 € c/IVA | 66–149 | Leroy Merlin, duchas termostáticas/monomando (SENSEA Icone 179) |
| Espejo LED (60–80 cm) | 1 | 70–150 € c/IVA | 58–124 | Leroy Merlin, espejos LED (ofertas 104,95–131,99) |
| **Total productos (rango)** | | **≈ 1.055–1.805 € c/IVA** | **≈ 873–1.490 €** | |

*(La mampara de vidrio templado ya está incluida en la partida 07.07.01.020.)*

### 3.1. Coste total del escenario baño (rango)

| Concepto | € (sin IVA) |
|---|---|
| Partidas de obra (CotizaT ES, MO a tarifa de mercado) | 2.362 |
| Productos finales (rango investigado) | +873 a +1.490 |
| Coste total estimado a tarifa CotizaT | ≈ 3.235 – 3.852 |
| **Coste directo real (MO en nómina a convenio + materiales; ficha [coste-laboral](coste-laboral-real-empleados-2026.md))** | **≈ 3.391 – 3.433 €** |
| **PVP propuesto — mercado 2026 (sin IVA)** | **≈ 5.800 – 6.400 €** |
| **Precio al cliente (IVA 10 %)** | **≈ 6.400 – 7.000 €** |
| Margen real sobre coste directo | ≈ 78–88 % |

> El PVP propuesto queda en la banda **media-baja del mercado real 2026** de reforma
> completa de baño 4–6 m² (5.000–8.000 € c/IVA: presunow, lebenproyectos, reformatucasa,
> reformas10), frente al anterior ≈ 4.800–5.300 c/IVA que Rubén marcó como 20–30 % bajo.
> Ajustar calidades (productos) sube/baja el coste; el PVP se fija contra la banda de
> mercado, no contra el coste.

## 4. Contraste con el mercado (España 2026, fuentes públicas)

| Fuente | Reforma completa de baño (2026) |
|---|---|
| ReforMatch | Media 5.500 €; rango habitual 2.500–12.000 €; baño de 5 m² con calidades medias **4.000–6.000 €**; 800–1.200 €/m² |
| Construdeco | Completa (demoliciones, electricidad y fontanería, ducha, alicatado, sanitarios): **4.500–7.000 €**; premium desde 8.500 € |
| Ferhogar | Completa: media **3.000–9.000 €**; gama media-alta **900–1.800 €/m²** |

→ Coherente. Validar con presupuestos reales locales en cuanto Rubén esté en A Coruña.

## 5. Próximos pasos

- [ ] Presupuestar el bloque de productos (proveedores de A Coruña) y cerrar el rango total.
- [ ] Repetir el mismo método para la **obra tipo cocina** y para la **integral por m²**.
- [ ] Validar el escenario contra 2-3 presupuestos reales pedidos (o recibidos) en la zona.
- [ ] Decidir margen objetivo por tipo de obra y política de "calidades estándar vs. alta".
- [ ] Convertir este modelo en plantilla de presupuesto (`09-plantillas/presupuesto.md`).

## Fuentes y trazabilidad

- Costes de partidas y recursos: CotizaT (repo `gtrespana-bit/generador-comercial`),
  archivos `basedatos_partidas/datos/descompuestos/*.json` y
  `basedatos_partidas/salida/precios_recursos_espana.csv` (2026-08-25).
- Referencias de mercado de reforma de baño: ReforMatch 2026, Construdeco 2026, Ferhogar 2026
  (enlaces recogidos el 2026-09-03; ver notas de la búsqueda).
