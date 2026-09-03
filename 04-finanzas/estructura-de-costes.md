# Estructura de costes — Piloto: obra tipo "reforma integral de baño estándar" (4,5 m²)

- **Fecha:** 2026-09-03
- **Estado:** `[BORRADOR]` — modelo piloto para validar el método de costes.
  Pendiente de validar con proveedores locales de A Coruña y con presupuestos reales.
- **Método:** partidas descompuestas de **CotizaT** (`generador-comercial`, repo propio de
  Rubén) valoradas con los **recursos de España en €** de
  `basedatos_partidas/salida/precios_recursos_espana.csv` (fecha datos: 2026-08-25,
  fuente de cada precio indicada en el CSV). Cálculo reproducible: coste partida =
  Σ(precio recurso ES × rendimiento del recurso en la partida).
- **Moneda:** €, **sin IVA** (a un presupuesto de venta se añade IVA 21 %).
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
| Precio de venta orientativo con margen 35 % (margen tipo CotizaT) | ≈ 3.188 € |
| Precio de venta orientativo con margen 25 % | ≈ 2.952 € |

> Notas de interpretación:
> - La mano de obra está valorada con las **tarifas de mercado ES** de CotizaT
>   (oficial 1.ª ~21-24 €/h, ayudante 15 €/h). Si la obra se ejecuta con **empleados
>   propios**, el coste empresa real es menor (17-20 €/h) → el margen mejora.
> - CotizaT usa por defecto un margen del 35 % sobre cada partida para formar precio de
>   venta; es una referencia, no una imposición.

## 3. Productos finales a añadir (PENDIENTE de presupuestar)

Estas partidas **no incluyen el producto final** (en CotizaT se añade como "producto
presupuestado"). Hay que presupuestarlos con proveedor local (A Coruña) y/o almacén:

| Producto | Para | Estado |
|---|---|---|
| Porcelanato/cerámica de pared (17 m² + mermas) | Alicatado | `[PENDIENTE]` precio proveedor |
| Porcelanato de suelo (4,5 m² + mermas) | Solado | `[PENDIENTE]` |
| Inodoro (estándar o suspendido) | Sanitario | `[PENDIENTE]` |
| Lavabo + mueble de baño | Sanitario | `[PENDIENTE]` |
| Plato de ducha | Ducha | `[PENDIENTE]` |
| Griferías (lavabo y ducha) | Grifería | `[PENDIENTE]` |
| Espejo (con o sin luz) y accesorios | Acabados | `[PENDIENTE]` |

**Referencia de mercado del bloque (España 2026, para orientar):** el conjunto de
sanitarios y grifería (inodoro, lavabo con mueble, plato de ducha y grifería) puede ir
**desde ~800 € (línea básica) hasta ~3.500 € o más (marcas de diseño)**, según datos de
ReforMatch (2026). (El precio de la mampara de vidrio ya está incluido en la partida
07.07.01.020 del cuadro anterior.)

## 4. Contraste con el mercado (España 2026, fuentes públicas)

| Fuente | Reforma completa de baño (2026) |
|---|---|
| ReforMatch | Media 5.500 €; rango habitual 2.500–12.000 €; baño de 5 m² con calidades medias **4.000–6.000 €**; 800–1.200 €/m² |
| Construdeco | Completa (demoliciones, electricidad y fontanería, ducha, alicatado, sanitarios): **4.500–7.000 €**; premium desde 8.500 € |
| Ferhogar | Completa: media **3.000–9.000 €**; gama media-alta **900–1.800 €/m²** |

→ El escenario CotizaT (2.362 € de partidas) + el bloque de productos (rango de mercado)
sitúa el total en una franja razonable **dentro del mercado** de reforma completa de baño.
Validar con presupuestos reales locales en cuanto Rubén esté en A Coruña.

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
