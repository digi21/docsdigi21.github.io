# RAYAR

Raya el interior de una entidad superficial de contorno cerrado.

## Parámetros

Si no se realiza ninguna asignación previa de [AA](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/AA.html) y [DA](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/DA.html), el sistema toma por defecto los valores cero para estos parámetros.

| Número de parámetro | Descripción | Valores | Opcional |
| :--- | :--- | :--- | :--- |
| 1 | Distancia activa principal \([DA](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/DA.html)\) | Número real | Si |
| 2 | Ángulo activo \([AA](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/AA.html)\) | Número real | Si |
| 3 | Código activo \([COD](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/COD.html)\) | Código puntual | Si |

## Observaciones

La dirección de las rayas está condicionada por el ángulo activo, y se hayan separadas una distancia igual al primer valor de la distancia activa.

## Características de la orden

| Tipo de orden | [Orden interactiva](rayar.md) |
| :--- | :--- |
| Repite automáticamente | Si |
| Opción del menú donde aparece la orden | Dibujar/Más/Rellenar polígono con rayas paralelas |
| Barra de herramientas en la que aparece la orden | _Esta orden no tiene asociado ningún botón en ninguna barra de herramientas_ |
| Extensión | DigiNG.OrdenesStandard.dll |
| Variables relacionadas | [AA](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/AA.html), [DA](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/DA.html), [REPITE](/digi3d-net/referencia/digi3d.net/ventana-de-dibujo/ordenes/r/REPITE.html) |

