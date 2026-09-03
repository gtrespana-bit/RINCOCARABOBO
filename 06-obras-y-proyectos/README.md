# 06 — Obras y proyectos

**Propósito:** archivo de las **obras reales** (presupuestos ofrecidos y proyectos ejecutados)
cuando el negocio arranque. Cada obra o cliente importante recibe su propia carpeta.

## Esquema por obra (crear cuando haga falta)

```
06-obras-y-proyectos/
└── AAAA-NNN_breve-descripcion/        (ej. 2027-001_reforma-integral-avda-marineda)
    ├── 00-cliente-y-contrato/         (datos de contacto, contrato firmado)
    ├── 01-presupuesto/                (presupuesto enviado, modificados)
    ├── 02-proyecto-y-planos/          (mediciones, planos, documentación técnica)
    ├── 03-fotos/                      (fotos del antes, durante y después)
    ├── 04-compras-y-facturas/         (facturas de materiales y subcontratas)
    └── 05-licencias-y-documentos/     (permisos, comunicaciones, garantías)
```

## Proyectos históricos (previos a esta empresa)

La subcarpeta [`historicos-espana/`](historicos-espana/README.md) guarda las fichas internas de
los **7 proyectos reales ejecutados por Rubén en España** (antes de abrir la empresa de
A Coruña). Son material de credibilidad para el plan de negocio y el futuro portfolio, con
los datos reales (ubicación, año) aún pendientes de confirmar.

## Reglas

- La numeración `AAAA-NNN` es por año; el nombre debe permitir identificar la obra sin abrirla.
- No mezclar facturas de varias obras: cada obra lleva sus propios números.
- Las **fotos del antes/después** de cada obra son el mejor material de marketing futuro
  (copia de las mejores a [`07-web-y-marketing/imagenes`](../07-web-y-marketing/imagenes/README.md)
  cuando toque).
- Plantillas para fichas de obra y presupuestos: ver [`09-plantillas`](../09-plantillas/README.md).
