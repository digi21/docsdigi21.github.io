# Code

Espacio de nombres: [Digi21.DigiNG.Entities](../../)\
Ensamblado: [Digi21.DigiNG](../../../)

Esta clase representa un código de la tabla de códigos.

```csharp
public struct Code
```

Herencia [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0) → [ValueType](https://docs.microsoft.com/en-us/dotnet/api/system.valuetype?view=net-5.0) → Code

## Constructores

|                                                                  |                                                                                                                                          |
| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| [Code(string)](constructores.md#code-string)                     | Inicializa una nueva instancia de [Code ](./)asignándole un nombre.                                                                      |
| [Code(string, int?, int?)](constructores.md#code-string-int-int) | Inicializa una nueva instancia de [Code ](./)asignándole un nombre, identificador de tabla de base de datos e identificador de registro. |
| [Code(string, int, int)](constructores.md#code-string-int-int-1) | Inicializa una nueva instancia de [Code ](./)asignándole un nombre, identificador de tabla de base de datos e identificador de registro. |

## Propiedades

|                                                                             |                                                                                                                                 |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| [Attributes](propiedades/attributes.md)                                     | Devuelve o asigna un diccionario con los atributos de base de datos asociados con el código.                                    |
| [Name](propiedades/name.md)                                                 | Devuelve el nombre del [Code](./).                                                                                              |
| [Table](propiedades/table.md)                                               | Devuelve el identificador de tabla de base de datos asociado con el [Code](./).                                                 |
| [Id](propiedades/id.md)                                                     | Devuelve el valor del _PrimaryKey_ del registro de base de datos al que apunta la geometría que tiene asignado este [Code](./). |
| [Visible](propiedades/visible.md)                                           | Indica si está habilitada la visualización de este [Code](./) en la ventana de dibujo.                                          |
| [VisiblePhotogrammetricWindow](propiedades/visiblephotogrammetricwindow.md) | Indica si está habilitada la visualización de este [Code](./) en la ventana fotogramétrica.                                     |

## Métodos estáticos

|                                                         |                                                                                                                     |
| ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| [Compare(string, string)](metodos-estaticos/compare.md) | Comprara utilizando la lógica de comodines de Digi3D.NET dos nombres de códigos.                                    |
| [Compose(string, string)](metodos-estaticos/compose.md) | Compone el nombre de un código a partir de un nombre de código existente y de una cadena a sustituir con comodines. |

## Métodos

|            |                                                                                                                                                                                                     |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ToString() | <p>Convierte este <a href="./">Code</a> en una cadena legible para los humanos.</p><p>(Heredado de <a href="https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0">Object</a>)</p> |

## Operadores

|    |   |
| -- | - |
| == |   |
| != |   |
