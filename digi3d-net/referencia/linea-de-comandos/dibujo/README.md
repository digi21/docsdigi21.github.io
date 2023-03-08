# dibujo

Ordena abrir una ventana de dibujo.

Este comando tiene una serie de subcomandos, así como una serie de opciones.

## Opciones

Estos valores son opcionales, y si se especifican modifican el valor por defecto que tienen asignados.

| Opción    | Descripción                                                                                                                                        | Valor por defecto |
| --------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- |
| --tabla   | Tabla de códigos                                                                                                                                   |                   |
| --escala  | Escala de visualización de patrones                                                                                                                | 1000.0            |
| --incr    | Incremento de registro                                                                                                                             | 1.0               |
| --equidis | Equidistancia de curvas de nivel                                                                                                                   | 1.0               |
| --genera  | Tolerancia a generalizar                                                                                                                           | 0.04              |
| --corrZ   | Corrección de Z                                                                                                                                    | 0.0               |
| --sigma   | Sigma                                                                                                                                              | 0.001             |
| --orden   | Orden a ejecutar al abrir la ventana de dibujo (puede ser el nombre de cualquier orden de Digi3D así como cualquier archivo de macroinstrucciones) |                   |

## Subcomandos

| Comando         | Descripción                                                                                                                             |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| [bind](bind.md) | Indica que se va a abrir un archivo de dibujo en formato .bind (binario de doble precisión)                                             |
| [bin](bin.md)   | Indica que se va a abrir un archivo de dibujo en formato .bin (binario de precisión simple)                                             |
| [shp](shp.md)   | Indica que el archivo de dibujo a abrir en la ventana de dibujo son los archivos _shapefile_ localizados en el directorio especificado. |

##
