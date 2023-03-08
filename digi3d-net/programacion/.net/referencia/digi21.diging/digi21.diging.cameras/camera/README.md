# Camera

Espacio de nombres: [Digi21.DigiNG.Cameras](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/)  
Ensamblado: [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)

Esta clase abstracta sirve como base para los distintos tipos de cámaras que soporta la ventana de dibujo de Digi3D.NET.

```csharp
public abstract class Camera
```

Herencia [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0) → Camera

Tipos derivados: [ConicCamera](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/coniccamera/)

## Propiedades

|  |  |
| :--- | :--- |
| [Far](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/camera/propiedades/far.md) | Devuelve o asigna la distancia del plano lejano del cono de visión. |
| [Near](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/camera/propiedades/near.md) | Devuelve o asigna la distancia del plano cercano del cono de visión. |
| [Name](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.entities/clases/code/propiedades/name.md) | Devuelve o asigna el nombre de la cámara. |
| [Pitch](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/camera/propiedades/pitch.md) de rotación en el eje _Pitch_. |
| [Position](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/camera/propiedades/position.md) | Devuelve o asigna la posición de la cámara. |
| [Roll](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/camera/propiedades/roll.md) de rotación en el eje _Roll_. |
| [Yaw](/digi3d-net/programacion/.net/referencia/digi21.diging/digi21.diging.cameras/clases/camera/propiedades/yaw.md) de rotación en el eje _Yaw_. |

## Métodos

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">ToString()</td>
      <td style="text-align:left">
        <p>Convierte este <a href="../../digi21.diging.entities/entity/">Entity</a> en
          una cadena legible para los humanos.</p>
        <p>(Heredado de <a href="https://docs.microsoft.com/en-us/dotnet/api/system.object?view=net-5.0">Object</a>)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="metodos/viewporttoworld.md">ViewportToWorld(Point3D)</a>
      </td>
      <td style="text-align:left">Transforma una coordenada de <em>c&#xE1;mara</em> a <em>mundo</em>.</td>
    </tr>
    <tr>
      <td style="text-align:left"><a href="metodos/worldtoviewport.md">WorldToViewport(Point3D)</a>
      </td>
      <td style="text-align:left">Transforma una coordenada de <em>mundo</em> a <em>c&#xE1;mara</em>.</td>
    </tr>
  </tbody>
</table>

