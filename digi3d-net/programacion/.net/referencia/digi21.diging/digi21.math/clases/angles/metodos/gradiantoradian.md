# GradianToRadian

Espacio de nombres: [Digi21.Math](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Transforma un ángulo centesimal a radián.

```csharp
public static double GradianToRadian(this double gradian);
```

## Parámetros

`gradian`[Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=net-5.0)  
Ángulo en centesimal a transformar.

## Devuelve

[Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=net-5.0)  
Valor transformado en radianes.

## Ejemplos

El siguiente ejemplo solicita al usuario un ángulo en centesimal y lo muestra en radianes:

```csharp
Console.Write("Introduce un ángulo en centesimal: ");
var centesimal = double.Parse(Console.Read());

Console.WriteLine($"Radianes: {Angles.GradianToRadian(centesimal)}");
```

