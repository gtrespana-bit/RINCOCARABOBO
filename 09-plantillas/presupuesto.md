# Plantilla de presupuesto de obra — RemodelaT Coruña S.L.

> Estado: `[BORRADOR]` (2026-09-03, actualizado a la recalibración de precios de Rubén:
> los PVP modelo estaban 20–30 % por debajo de mercado). Uso interno: **solo para obras
> reales** — al salir una obra se prepara su oferta con CotizaT + las bandas del
> tarifario; no se generan presupuestos tipo a cliente (decisión Rubén, 2026-09-03).
> **Regla de precio:** el PVP se fija en la banda de mercado 2026 (nunca por debajo del
> punto bajo-medio documentado; ver
> [04-finanzas/calibracion-tarifas-mercado-2026.md](../04-finanzas/calibracion-tarifas-mercado-2026.md));
> CotizaT se usa para medición (m², horas) y el coste real (nómina + materiales) para
> validar el margen. **Ninguna cifra inventada.**

## Estructura del presupuesto (por capítulos)

Un presupuesto de reforma debe estar **desglosado por capítulos y partidas**, con su
medición, para que el cliente entienda qué incluye y qué no.

```
PRESUPUESTO N.º ____                                        Fecha: __/__/____
Cliente:  [Nombre]                     NIF/CIF: [__]
Obra / dirección: [calle, ciudad]      Teléfono/email: [__]
Válido hasta: [30 días]

0. OBJETO Y ALCANCE
   Descripción breve de la obra y del nivel de acabado (estándar/medio/alto).
   Relación de estancias y superficie.

1. ACTUACIONES PREVIAS Y DEMOLICIONES
   | Código | Partida | Un | Cant. | Precio € | Importe € |
   |---|---|---|---|---|---|
   | (CotizaT) | Desmontaje de... | ud | ... | ... | ... |

2. ALBAÑILERÍA Y REVESTIMIENTOS
   (regularizaciones, alicatados, solados, tabiques…)

3. INSTALACIONES
   (agua, desagües, electricidad, iluminación, ventilación…)

4. CARPINTERÍA
   (puertas, marcos…)

5. SANITARIOS, GRIFERÍA Y MOBILIARIO (productos)
   | Producto | Marca/modelo | Un | Cant. | Precio € | Importe € |

6. COCINA (si aplica)
   (muebles, encimera, electrodomésticos, fregadero…)

7. PINTURA Y ACABADOS

8. RESIDUOS Y LIMPIEZA

9. PRUEBAS Y CONTROLES

   TOTAL PARTIDAS (sin IVA)                      ________ €
   BASE IMPONIBLE (PVP = banda de mercado 2026)  ________ €
   IVA (10 % vivienda habitual / 21 %)           ________ €
   TOTAL PRESUPUESTO                             ________ €
```

## Condiciones del presupuesto (texto a incluir siempre)

1. **Precios:** en euros, con IVA indicado aparte (base imponible + IVA). Tipo aplicable:
   **10 %** en reforma de vivienda habitual (obra > 2 años desde su construcción) o 21 %
   en el resto — confirmar con gestoría antes de la primera factura.
2. **Validez:** 30 días naturales desde la fecha (los precios de materiales varían).
3. **Forma de pago (confirmada por Rubén):** **50 % a la firma / 20 % / 20 % por hitos /
   10 % a la entrega** (con la garantía por escrito).
4. **Plazo de ejecución:** __ semanas desde el inicio, condicionado a permisos, entregas de
   materiales y climatología. Plazo orientativo, no vinculante si hay causas ajenas.
5. **No incluido en este presupuesto** (lista de exclusiones explícita, p. ej.):
   - Modificaciones estructurales no contempladas.
   - Carpintería exterior (ventanas/puerta de entrada) salvo que se indique.
   - Calefacción, ACS, climatización o sistemas eléctricos especiales.
   - Tasa/licencia municipal, proyecto técnico, seguridad y salud, si fueran necesarios.
   - Mudanza/guardamuebles, traslados del cliente.
   - Imprevistos no visibles en la visita (humedades ocultas, instalaciones en mal estado,
     soportes que exijan refuerzos): se presupuestarán como modificación con su partida.
   - Limpieza de la vivienda más allá de la limpieza final de obra de la zona intervenida.
6. **Modificaciones:** cualquier cambio de alcance durante la obra se documenta por escrito
   (modificado) con su importe antes de ejecutarse.
7. **Garantía:** ___ años por escrito sobre los trabajos ejecutados, según el alcance y las
   condiciones de cada partida (materiales garantizados por su fabricante).
8. **Acceso y condiciones de obra:** el cliente facilitará acceso, agua y luz durante la
   obra; la entrada de material y la gestión de escombros se harán según normativa de la
   comunidad/edificio.
9. La aceptación de este presupuesto se formaliza con la firma del cliente y del
   contratista, y con el [contrato de obra](contrato-de-obra.md).

## Notas de cálculo interno (no se entregan al cliente)

- Coste de mano de obra con **empleados propios**: coste empresa real (convenio
  construcción A Coruña 2026 + SS 2026; oficial/ayudante 17–20 €/h, grupo ≈ 34–35 €/h
  dúo) — ver [coste-laboral-real](../04-finanzas/coste-laboral-real-empleados-2026.md).
  CotizaT solo para **mediciones y horas** (nunca sus precios como PVP: quedaban 20–30 %
  bajo de mercado).
- Productos: precio investigado (Obramat/Leroy Merlin u otro proveedor, con fecha) o
  presupuesto de proveedor local (A Coruña).
- PVP de partida (p. ej. suelo cerámico colocado, demoliciones): usar las bandas de
  mercado de la [calibración](../04-finanzas/calibracion-tarifas-mercado-2026.md).
- Contingencias e imprevistos: **política Rubén (2026-09-03)** — precio cerrado; los
  imprevistos ocultos o cambios se documentan y presupuestan como **modificación** que el
  cliente aprueba; la empresa no los absorbe.
- Revisar cada partida con el método RemodelaT (etapa 4: presupuesto por partidas con sus
  exclusiones).
