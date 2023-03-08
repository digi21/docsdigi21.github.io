# RadianToSexagesimal

Espacio de nombres: [Digi21.Math](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.math/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Transforma un ángulo radián a sexagesimal.

```csharp
public static double RadianToSexagesimal(this double radian);
```

## Parámetros

`radian`[Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=net-5.0)  
Ángulo en radianes a transformar.

## Devuelve

[Double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=net-5.0)  
Valor transformado en sexagesimal.

## Ejemplos

El siguiente ejemplo solicita al usuario un ángulo en radianes y lo muestra en sexagesimal:

```csharp
Console.Write("Introduce un ángulo en radianes: ");
var radianes= double.Parse(Console.Read());

Console.WriteLine($"Centesimal: {Angles.RadianToSexagesimal(radianes)}");
```

