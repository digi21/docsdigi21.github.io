# Deleted

Espacio de nombres: [Digi21.DigiNG.Entities](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Especifica la geometría representada por este [Entity](../)está eliminada.

```csharp
public bool Deleted { get; }
```

## Valor de la propiedad

[Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=net-5.0)

Verdadero si la geometría está marcada como eliminada. Falso en caso contrario.

## Observaciones

Al llamar al método [IDrawingFile.Delete](../../../../digi21.diging.io/interfaces/idrawingfile/metodos/delete.md) la geometría se marca como eliminada pero no se elimina realmente del archivo de dibujo. La manera de eliminar realmente una geometría de un archivo de dibujo es creando un archivo de dibujo nuevo en el que no se almacene la geometría en cuestión.

Esta operación es la que realiza internamente la orden [COMPRIMIR](/digi3d-net/referencia/ventana-de-dibujo/ordenes/c/comprimir.md) de Digi3D.NET.

