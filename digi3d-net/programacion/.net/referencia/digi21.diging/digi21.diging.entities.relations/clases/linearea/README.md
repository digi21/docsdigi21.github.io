# LineArea

Espacio de nombres: [Digi21.DigiNG.Entities.Relations](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities.relations/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Esta clase estática proporciona métodos que permiten analizar la relación entre líneas y áreas.

```csharp
public static class LineArea
```

Herencia [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0) → AreaArea

## Observaciones

Un _Área_ en este contexto se refiere a líneas cerradas, de manera que engloba tanto a cualquier geometría de tipo [ReadOnlyPolygon](../../../digi21.diging.entities/clases/readonlypolygon/)o cualquier [ReadOnlyLine](../../../digi21.diging.entities/clases/readonlyline/)que esté cerrado.

El resultado de uno de estos métodos estáticos es excluyente, lo que significa que, si [Across](metodos-estaticos/across.md)devuelve _Verdadero_, forzosamente [Disjoint](../areaarea/metodos-estaticos/disjoint.md)devolverá _Falso_.

Estos métodos únicamente analizan vértices existentes, es decir, que si no hay un vértice común entre las dos geometrías que se cruzan, su cruce pasará desapercibido.

## Métodos estáticos

|  |  |
| :--- | :--- |
| [Across\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/across.md#across-readonlyline-readonlyline) | Indica si la línea cruza el área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [Across\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/across.md#across-readonlyline-readonlypolygon) | Indica si la línea cruza el área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |
| [Adjacent\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/adjacent.md#adjacent-readonlyline-readonlyline) | Indica si la línea es adyacente al área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [Adjacent\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/adjacent.md#adjacent-readonlyline-readonlypolygon) | Indica si la línea es adyacente al área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |
| [Disjoint\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/disjoint.md#disjoint-readonlyline-readonlyline) | Indica si la línea es disjunta al área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [Disjoint\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/disjoint.md#disjoint-readonlyline-readonlypolygon) | Indica si la línea es adyacente al área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |
| [EndpointJoin\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/endpointjoin.md#endpointjoin-readonlyline-readonlyline) | Indica si uno de los extremos de la línea finaliza en el área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [EndpointJoin\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/endpointjoin.md#endpointjoin-readonlyline-readonlypolygon) | Indica si uno de los extremos de la línea finaliza en el área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |
| [Join\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/join.md#join-readonlyline-readonlyline) | Indica si la línea se une en alguno de sus puntos en el área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [Join\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/join.md#join-readonlyline-readonlypolygon) | Indica si la línea se une en alguno de sus puntos en el área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |
| [TerminatesWithin\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/terminateswithin.md#terminateswithin-readonlyline-readonlyline) | Indica si uno de los extremos de la línea finaliza dentro del área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [TerminatesWithin\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/terminateswithin.md) | Indica si uno de los extremos de la línea finaliza dentro del área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |
| [Within\(ReadOnlyLine, ReadOnlyLine\)](metodos-estaticos/within.md#within-readonlyline-readonlyline) | Indica si la línea está completamente dentro del área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/). |
| [Within\(ReadOnlyLine, ReadOnlyPolygon\)](metodos-estaticos/within.md#within-readonlyline-readonlypolygon) | Indica si la línea está completamente dentro del área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |

