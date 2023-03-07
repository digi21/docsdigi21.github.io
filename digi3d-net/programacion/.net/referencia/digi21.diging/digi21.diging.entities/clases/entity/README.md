# Entity

Espacio de nombres: [Digi21.DigiNG.Entities](../../)\
Ensamblado: [Digi21.DigiNG](../../../)

Esta clase abstracta es la clase base común de todas las clases que implementan geometrías.

```csharp
public abstract class Entity : IWindow3D, ICloneable, IDisposable
```

Herencia [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0) → Entity

Tipos derivados: [ReadOnlyComplex](../readonlycomplex/), [ReadOnlyLine](../readonlyline/), [ReadOnlyPoint](../readonlypoint/), [ReadOnlyPolygon](../readonlypolygon/), [ReadOnlyText](../readonlytext/).

Implementa: [ICloneable](../../interfaces/icloseable/), [IWindow3D](../../../digi21.math/interfaces/iwindow3d/)

## Observaciones

Algunas propiedades de este tipo permiten asignación como [FillColor](propiedades/fillcolor.md), [Weigtht ](propiedades/weight.md)y [Color](propiedades/color.md), [Hidden](propiedades/hidden.md).

Al instanciar una geometría nueva como por ejemplo [Line](../line/), ésta es de lectura/escritura, de manera que se pueden utilizar las propiedades de asignación sin ningún problema. \
En el momento en el que la geometría se almacena en un archivo de dibujo ([IDrawingFile](../../../digi21.diging.io/interfaces/idrawingfile/)), esta se convierte en una geometría de sólo lectura y ya no es posible asignar ninguna propiedad.&#x20;

En caso de asignar alguna propiedad en una geometría de solo lectura (excepto la propiedad [Hidden](propiedades/hidden.md)), el runtime lanzará una excepción de tipo [InvalidOperationException](https://docs.microsoft.com/en-us/dotnet/api/system.invalidoperationexception?view=net-5.0).

## Propiedades

| [Attributes](propiedades/attributes\_entity.md)                           | Devuelve o asigna un diccionario con los atributos de la geometría                                                                                                     |
| ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [W](../../../digi21.math/interfaces/iwindow3d/propiedades/w.md)           | <p>Devuelve el punto al oeste del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                  |
| [SW](../../../digi21.math/interfaces/iwindow3d/propiedades/sw.md)         | <p>Devuelve el punto al sudeste del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                |
| [S](../../../digi21.math/interfaces/iwindow3d/propiedades/s.md)           | <p>Devuelve el punto al sur del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                    |
| [SE](../../../digi21.math/interfaces/iwindow3d/propiedades/se.md)         | <p>Devuelve el punto al sudeste del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                |
| [E](../../../digi21.math/interfaces/iwindow3d/propiedades/e.md)           | <p>Devuelve el punto al este del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                   |
| [NE](../../../digi21.math/interfaces/iwindow3d/propiedades/ne.md)         | <p>Devuelve el punto al noreste del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                |
| [N](../../../digi21.math/interfaces/iwindow3d/propiedades/n.md)           | <p>Devuelve el punto al norte del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                  |
| [NW](../../../digi21.math/interfaces/iwindow3d/propiedades/nw.md)         | <p>Devuelve el punto al noreste del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                |
| [Center](../../../digi21.math/interfaces/iwindow3d/propiedades/center.md) | <p>Devuelve el punto en el centro del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>              |
| [Depth](../../../digi21.math/interfaces/iwindow3d/propiedades/depth.md)   | <p>Devuelve el largo del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                           |
| [Height](../../../digi21.math/interfaces/iwindow3d/propiedades/height.md) | <p>Devuelve el alto del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                            |
| [Width](../../../digi21.math/interfaces/iwindow3d/propiedades/width.md)   | <p>Devuelve el ancho del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>                           |
| [Valid](../../../digi21.math/interfaces/iwindow3d/propiedades/valid.md)   | <p>Indica si las máximas y mínimas del <a href="./">Entity</a> son válidas.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p> |
| [Xmin](../../../digi21.math/interfaces/iwindow3d/propiedades/xmin.md)     | <p>Devuelve la coordenada X mínima del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>             |
| [Ymin](../../../digi21.math/interfaces/iwindow3d/propiedades/ymin.md)     | <p>Devuelve la coordenada Y mínima del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>             |
| [Zmin](../../../digi21.math/interfaces/iwindow3d/propiedades/zmin.md)     | <p>Devuelve la coordenada Z mínima del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>             |
| [Xmax](../../../digi21.math/interfaces/iwindow3d/propiedades/xmax.md)     | <p>Devuelve la coordenada X máxima del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>             |
| [Ymax](../../../digi21.math/interfaces/iwindow3d/propiedades/ymax.md)     | <p>Devuelve la coordenada Y máxima del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>             |
| [Zmax](../../../digi21.math/interfaces/iwindow3d/propiedades/zmax.md)     | <p>Devuelve la coordenada Z máxima del <a href="./">Entity</a>.</p><p>(Heredado de <a href="../../../digi21.math/interfaces/iwindow3d/">IWindow3D</a>)</p>             |
| [Owner](propiedades/owner.md)                                             | Devuelve el [IDrawingFile ](../../../digi21.diging.io/interfaces/idrawingfile/)al que pertenece el [Entity](./).                                                       |
| [Deleted](propiedades/deleted.md)                                         | Especifica si el [Entity ](./)está eliminado.                                                                                                                          |
| [ReadOnly](propiedades/readonly.md)                                       | Especifica si el [Entity](./) es de solo lectura (ya está almacenada en algún [IDrawingFile](../../../digi21.diging.io/interfaces/idrawingfile/))                      |
| [FillColor](propiedades/fillcolor.md)                                     | Especifica el color de relleno del [Entity](./).                                                                                                                       |
| [Weight](propiedades/weight.md)                                           | Especifica el grosor del [Entity](./).                                                                                                                                 |
| [Color](propiedades/color.md)                                             | Especifica el color del [Entity](./).                                                                                                                                  |
| [Codes](propiedades/codes.md)                                             | Devuelve un objeto [CodeCollection ](broken-reference)con los códigos del [Entity](./).                                                                                |
| [Visible](propiedades/visible.md)                                         | Indica si el [Entity](./) es visible.                                                                                                                                  |
| [CreationTime](propiedades/creationtime.md)                               | Devuelve un objeto [DateTime ](https://docs.microsoft.com/en-us/dotnet/api/system.datetime?view=net-5.0)con la fecha de creación del [Entity](./).                     |
| [Offset](propiedades/offset.md)                                           | Indica el _offset_ en el que está almacenado el [Entity](./) en el [IDrawingFile](../../../digi21.diging.io/interfaces/idrawingfile/).                                 |
| [Hidden](propiedades/hidden.md)                                           | Comprueba y permite indicar si ocultar la visualización de este [Entity](./) en la ventana de dibujo.                                                                  |

## Métodos

|                           |                                                                                                                                                                                                                                    |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Clone](metodos/clone.md) | <p>Instancia una nueva <a href="./">Entity </a>idéntica que no está almacenada en ningún archivo de dibujo y que por lo tanto no es de solo lectura.</p><p>(Heredado de <a href="../../interfaces/icloseable/">ICloneable</a>)</p> |
| ToString                  | <p>Convierte este <a href="./">Entity</a> en una cadena legible para los humanos.</p><p>(Heredado de <a href="https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0">Object</a>)</p>                              |
|                           |                                                                                                                                                                                                                                    |

