# BUSCAR\_CENTROIDE

Localiza el centroide dentro de un recinto, después de haber cargado uno o varios topológicos.

## Parámetros

No admite parámetros.

## Observaciones

Esta orden sólo se podrá ejecutar cuando haya uno o varios ficheros topológicos cargados en memoria.

Cuando se tiene cargado el archivo o archivos topológicos y se ejecuta la orden _BUSCAR\_CENTROIDE_ el programa indicará al usuario que digitalice un punto.

Al digitalizar un punto puede que esté o no dentro de algún recinto. En caso de no estar dentro de ningún recinto, la orden hace sonar el pitido de error y finaliza.

En caso de digitalizar el punto dentro de algún recinto el comportamiento será el siguiente:

* Si está activado el flag [VER](/digi3d-net/referencia/ventana-de-dibujo/variables/v/ver.md) y mostrará un globo indicando que se ha seleccionado un polígono sin centroide.
* Si está activado el flag [VER](/digi3d-net/referencia/ventana-de-dibujo/variables/v/ver.md).
* A continuación hace un zoom centrado en el centroide del polígono seleccionado si éste dispone de centroide. En el caso de que el polígono no tenga centroide, hará el zoom al centroide calculado automáticamente por la orden [BINTOP](/digi3d-net/referencia/ventana-de-dibujo/ordenes/b/bintop.md) y mostrará un globo indicando que se ha seleccionado un polígono sin centroide.

## Características de la orden

| Tipo de orden | [Orden interactiva](buscar-centroide.md) |
| :--- | :--- |
| Repite automáticamente | No |
| Opción del menú donde aparece la orden | _Esta orden no tiene asociada ninguna opción de menú_ |
| Barra de herramientas en la que aparece la orden | _Esta orden no tiene asociado ningún botón en ninguna barra de herramientas_ |
| Extensión | DigiNG.OrdenesStandard.dll |
| Variables relacionadas | No tiene variables relacionadas |

