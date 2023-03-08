# Point3D

Espacio de nombres: [Digi21.Math](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Esta clase implementa un punto en tres dimensiones.

```csharp
public struct Point3D : IDesplazable
```

Herencia [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0) → [ValueType](https://docs.microsoft.com/en-us/dotnet/api/system.valuetype?view=net-5.0) → Point3D

Implementa: [IDesplazable](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/interfaces/idesplazable/)

## Constructores

|  |  |
| :--- | :--- |
| Point3D\(Point2D\) | Inicializa una nueva instancia de [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md)copiando datos de un Point2D. |
| Point3D\(double\) | Inicializa una nueva instancia de [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md)asignando a las coordenadas X, Y, Z el valor pasado por parámetros. |
| Point3D\(double, double, double\) | Inicializa una nueva instancia de [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md) asignando a las coordenadas X, Y, Z los valores pasados por parámetros. |

## Propiedades

|  |  |
| :--- | :--- |
| X | Devuelve o asigna la coordenada X del [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| Y | Devuelve o asigna la coordenada Y del [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| Z | Devuelve o asigna la coordenada Y del [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| Point2D | Devuelve un [Point2D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point2d.md). |
| Module | Devuelve la distancia entre las coordenadas del [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| SquaredModule | Devuelve la distancia al cuadrado entre las coordenadas del [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| Normalized | Devuelve un nuevo [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md) cuyo módulo es 1.0. |
| IsEmpty | Devuelve verdadero si las coordenadas X,Y,Z son 0.0. |

## Métodos

|  |  |
| :--- | :--- |
| DotProduct\(Point2D, Point2D\) | Devuelve el producto escalar de dos [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| CrossProduct\(Point3D, Point3D\) | Devuelve el producto vectorial de dos [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| CalculateModule\(Point3D, Point3D\) | Calcula el módulo en el espacio entre un [Point3D](point3d.md)y un [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| CalculateModule\(Point3D, Point2D\) | Calcula el módulo en el espacio entre un [Point3D](point3d.md)y un [Point2D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point2d.md). |
| CalculateModule\(Point2D, Point3D\) | Calcula el módulo en el espacio entre un [Point2D](point2d.md)y un [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| CalculateModule\(Point2D, Point2D\) | Calcula el módulo en el espacio entre dos [Point2D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point2d.md). |
| CalculateSquaredModule\(Point3D, Point3D\) | Calcula el módulo en el espacio al cuadrado entre dos [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| [Offset\(Point2D\)](idesplazable/metodos/offset.md#offset-point-2-d) | Desplaza la geometría tantas unidades en X, Y como se indique en el parámetro. |
| [Offset\(Point3D\)](idesplazable/metodos/offset.md#offset-point-3-d) | Desplaza la geometría tantas unidades en X, Y, Z como se indique en el parámetro. |
| [Offset\(double, double\)](idesplazable/metodos/offset.md#offset-double-double) | Desplaza la geometría tantas unidades en X, Y como se indique en los parámetros. |
| [Offset\(double, double, double\)](idesplazable/metodos/offset.md#offset-double-doublem-double) | Desplaza la geometría tantas unidades en X, Y, Z como se indique en los parámetros. |
| ToString\(\) | Devuelve una cadena con la representación del punto. |

## Operadores

|  |  |
| :--- | :--- |
| Point2D | Transforma el [Point3D](point3d.md)en un [Point2D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point2d.md). |
| == | Devuelve verdadero si los dos [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md)tienen idénticas coordenadas. |
| != | Devuelve verdadero si los dos [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md)tienen distintas coordenadas. |
| + | Devuelve un [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| - | Devuelve un [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md). |
| \* | Devuelve un [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md) a la izquierda del operador por el escalar a la derecha del operador. |
| / | Devuelve un [Point3D](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/clases/point3d.md) a la izquierda del operador divididas por el escalar a la derecha del operador. |
|  |  |

