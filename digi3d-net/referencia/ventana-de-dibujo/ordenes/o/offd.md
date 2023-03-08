# OFFD

Desactiva el código \(o códigos\) que no se desean visualizar en la pantalla de dibujo, tanto en DigiNG como en la pantalla de visión estereoscópica.

## Parámetros

| Número de parámetro | Descripción | Opcional |
| :--- | :--- | :--- |
| 1 | Código/os que se ocultarán en la pantalla de dibujo | Si. Por defecto al abrir un fichero de dibujo aparecen todos los códigos visibles |

### Ejemplos

`OFFD=*`

Oculta todos códigos en pantalla

`OFFD=02*`

Oculta todos los códigos que comiencen por 02

`OFFD=020123`

Oculta solamente los elementos cuyo código sea 020123

## Observaciones

Podemos especificar el tipo de entidad a mostrar, para cada uno de los códigos: Líneas, Puntos ó Textos.

Digi3D nos permite cargar archivos de muestra de códigos o guardar uno que generemos nostros:

* Cargar de archivo...: carga un archivo de muestra de códigos previamente generado y guardado.
* Guardar en archivo...: podemos guardar mediante un nombre, la lista de códigos seleccionada para una posterior utilización. Los archivos generados estarán en formato .xml.

## Características de la orden

| Tipo de orden | [Orden interactiva](offd.md) |
| :--- | :--- |
| Repite automáticamente | No |
| Opción del menú donde aparece la orden | _Esta orden no tiene asociada ninguna opción de menú_ |
| Barra de herramientas en la que aparece la orden | _Esta orden no tiene asociado ningún botón en ninguna barra de herramientas_ |
| Extensión | DigiNG.OrdenesRaster.dll |
| Variables relacionadas | No tiene variables relacionadas |

