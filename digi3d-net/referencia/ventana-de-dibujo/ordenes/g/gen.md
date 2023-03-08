# GEN

Filtra o elimina puntos de una entidad seleccionada por el usuario.

## Parámetros

| Número de parámetro | Descripción | Valores | Opcional |
| :--- | :--- | :--- | :--- |
| 1 | [TOL](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/TOL.html) | Número real | Si |
| 2 | [TOL\_ANG](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/TOL_ANG.html) | Número real | Si |

## Observaciones

El modo de actuar depende del factor de generalización que se encuentre activo en el momento de ejecutar esta orden. Este factor está condicionado por las variables de tolerancia, cuyo valores se asignan mediante las órdenes [TOL](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/TOL.html) y [TOL\_ANG](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/TOL_ANG.html).

Si tecleamos `GEN=<código>`, se generalizarán todas las entidades con ese código que existan en el fichero de dibujo.

## Características de la orden

| Tipo de orden | [Orden interactiva](gen.md) |
| :--- | :--- |
| Repite automáticamente | Si |
| Opción del menú donde aparece la orden | Editar/Polilíneas/Generalizar |
| Barra de herramientas en la que aparece la orden | Editar polilínea |
| Extensión | DigiNG.OrdenesStandard.dll |
| Variables relacionadas | [REPITE](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/REPITE.html), [TOL](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/TOL.html), [TOL\_ANG](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/g/TOL_ANG.html) |

