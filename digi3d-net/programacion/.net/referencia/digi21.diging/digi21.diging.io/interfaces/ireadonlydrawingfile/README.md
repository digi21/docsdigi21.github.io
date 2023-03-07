# IReadOnlyDrawingFile

Espacio de nombres: [Digi21.DigiNG.IO](../../)\
Ensamblado: [Digi21.DigiNG](../../../)

Esta interfaz define los métodos que implementan los importadores/exportadores de solo lectura de archivos.

```csharp
public interface IReadOnlyDrawingFile : IEnumerable<Entity>
```

Tipos derivados: [IDrawingFile](../idrawingfile/)

Implementa: [IEnumerable\<Entity>](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1?view=net-5.0), [IWindow3D](../../../digi21.math/interfaces/iwindow3d/)

## Propiedades

| [ConnectionString](propiedades/connectionstring.md) | Devuelve la cadena de conexión de la base de datos asociada con el archivo de dibujo. |
| --------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [Path](propiedades/path.md)                         | Devuelve la ruta del archivo de dibujo.                                               |
| [Visible](propiedades/visible.md)                   | Indica/Establece la visibilidad del archivo en la ventana de dibujo.                  |

##

