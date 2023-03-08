# TerminatesWithin

Espacio de nombres: [Digi21.DigiNG.Entities.Relations](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities.relations/)\
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Indica si uno de los extremos de la línea está dentro del área.

![Línea termina en área](../../../../../../../../../.gitbook/assets/lineaterminaenarea.png)

## Sobrecargas

|                                                                                                                      |                                                                                                                                                           |
| -------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [TerminatesWithin(ReadOnlyLine, ReadOnlyLine)](terminateswithin.md#terminateswithin-readonlyline-readonlyline)       | Indica si uno de los extremos de la línea finaliza dentro del área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/).       |
| [TerminatesWithin(ReadOnlyLine, ReadOnlyPolygon)](terminateswithin.md#terminateswithin-readonlyline-readonlypolygon) | Indica si uno de los extremos de la línea finaliza dentro del área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/). |

## TerminatesWithin(ReadOnlyLine, ReadOnlyLine)

Indica si uno de los extremos de la línea finaliza dentro del área de tipo [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/).

```csharp
public static bool TerminatesWithin(ReadOnlyLine line, ReadOnlyLine area)
```

### Parámetros

`line` [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/)\
Línea.

`area` [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/)\
Área.

## Devuelve

[Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=net-5.0)\
_Verdadero_ si la línea finaliza dentro del área.

## TerminatesWithin(ReadOnlyLine, ReadOnlyPolygon)

Indica si uno de los extremos de la línea finaliza dentro del área de tipo [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/).

```csharp
public static bool TerminatesWithin(ReadOnlyLine line, ReadOnlyPolygon area)
```

### Parámetros

`line` [ReadOnlyLine](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlyline/)\
Línea.

`area` [ReadOnlyPolygon](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/readonlypolygon/)\
Área.

## Devuelve

[Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=net-5.0)\
_Verdadero_ si la línea finaliza dentro del área.
