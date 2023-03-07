# Attributes

Espacio de nombres: [Digi21.DigiNG.Entities](../../../)\
Ensamblado: [Digi21.DigiNG](../../../../)

Devuelve un diccionario con los atributos de la geometría.

```csharp
public IDictionary<string, object> Attributes { get;  }‌
```

## Valor de la propiedad <a href="#valor-de-la-propiedad" id="valor-de-la-propiedad"></a>

[IDictionary<>](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.idictionary-2?view=net-5.0)

Un diccionario de pares clave valor.

## Ejemplo

Para crear un código que tenga atributos de base de datos asociados:

```csharp
var código = new Line("020400")
{
    Attributes = new Dictionary<string, object>
    {
        {"Propietario", "Dylan"},
        {"Alturas", 3},
        {"Superficie", 200.0}
    }
};
```

