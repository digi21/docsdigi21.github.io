# Delete

Espacio de nombres: [Digi21.DigiNG.IO](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.io/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Elimina geometrías al archivo de dibujo.

## Sobrecargas

|  |  |
| :--- | :--- |
| [Delete\(Entity\)](delete.md#delete-entity) | Elimina un [Entity](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/entity/) del archivo de dibujo. |
| [Delete\(IEnumerable&lt;Entity&gt;\)](delete.md#delete-ienumerable-less-than-entity-greater-than) | Elimina una enumeración de [Entity](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/entity/) del archivo de dibujo. |

## Delete\(Entity\)

Elimina un [Entity](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/entity/) del archivo de dibujo.

```csharp
void Delete(Entity entity);
```

### Parámetros

`entity` [Entity](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/entity/)  
Geometría para eliminar del archivo de dibujo.

## Delete\(IEnumerable&lt;Entity&gt;\)

Elimina una enumeración de [Entity](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/entity/) del archivo de dibujo.

```csharp
void Delete(IEnumerable<Entity> entities);
```

`entities` [IEnumerable&lt;Entity&gt;](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerator-1?view=net-5.0)  
Geometrías a eliminar del archivo de dibujo.

