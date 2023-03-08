# SOLAPE

Establece el valor del porcentaje de solape de la ventana.

## Parámetros

| Número de parámetro | Descripción | Valores | Opcional |
| :--- | :--- | :--- | :--- |
| 1 | Valor numérico | Número real | Si |

### Observaciones

Las órdenes que van a utilizar _SOLAPE_ son [ZOOMDER](/digi3d-net/referencia/ventana-de-dibujo/ordenes/z/zoomder.md).

Este valor se da en tanto por ciento y su valor por defecto será del 10%.

### Ejemplos

`SOLAPE=25`

Asigna como solape el valor 25 %

`SOLAPE=?`

Muestra el valor actual del solape

## Características de la orden

| Tipo de orden | [Variable real](solape.md) |
| :--- | :--- |
| Repite automáticamente | No |
| Opción del menú donde aparece la orden | _Esta orden no tiene asociada ninguna opción de menú_ |
| Barra de herramientas en la que aparece la orden | _Esta orden no tiene asociado ningún botón en ninguna barra de herramientas_ |
| Extensión | DigiNG.OrdenesStandard.dll |
| Variables relacionadas | [REPITE](/digi3d-net/referencia/ventana-de-dibujo/variables/r/repite.md) |

