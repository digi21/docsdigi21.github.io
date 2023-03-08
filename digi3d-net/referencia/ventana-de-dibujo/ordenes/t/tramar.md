# TRAMAR

Trama el interior de una entidad superficial de contorno cerrado.

## Parámetros

Si no se especifica ningún parámetro, el sistema toma por defecto los valores cero y uno para [AA](/digi3d-net/referencia/ventana-de-dibujo/variables/a/aa.md) respectivamente.

| Número de parámetro | Descripción | Valores | Opcional |
| :--- | :--- | :--- | :--- |
| 1 | Ángulo activo | Número real | Si |
| 2 | Distancia activa | Número real | Si |

## Observaciones

El tramado se compone de un doble rayado cuya disposición depende de los valores que tengan asignados los parámetros [ángulo activo](/digi3d-net/referencia/ventana-de-dibujo/ordenes/t/AA.html) y [distancia activa](https://github.com/digi21/docs/tree/7fc627c885c16fb88afc7cc05a6df2a2f4a54563/digi3d-net/referencia/ventana-de-dibujo/ordenes/t/DA.md).

El primer rayado tiene la dirección del ángulo activo, y las rayas se hayan separadas una distancia igual al primer valor de la distancia activa. El segundo tramado tiene una dirección perpendicular al primero, y sus rayas están separadas una distancia igual al segundo valor de la distancia activa.

El conjunto de rayas que componen el tramado se representan con el código que estuviera activo al ejecutar la orden.

## Características de la orden

| Tipo de orden | [Orden interactiva](tramar.md) |
| :--- | :--- |
| Repite automáticamente | No |
| Opción del menú donde aparece la orden | Dibujar/Mas/Rellenar polígono con una trama |
| Barra de herramientas en la que aparece la orden | _Esta orden no tiene asociado ningún botón en ninguna barra de herramientas_ |
| Extensión | DigiNG.OrdenesStandard.dll |
| Variables relacionadas | [AA](/digi3d-net/referencia/ventana-de-dibujo/variables/a/aa.md) |

