# Errores de la geometría que se está analizando

El guion puede comunicar a Digi3D.NET que la geometría no cumple con el control de calidad lanzando una excepción excepción de tipo [GeometryException](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging.plugin.qualitycontrol/excepciones/geometryexception.md): 

```csharp
using System;
using Digi21.DigiNG.Entities;
using Digi21.DigiNG.Plugin.QualityControl;

namespace DigiTab
{
    public class Desencadenador : ITrigger 
    {
	      public Entity AnalyzeEntity(Entity entidad, bool almacenandoEntidad) 
		    {
		        if( !(entidad is ReadOnlyLine) )
		            throw new GeometryException(String.Format("Las geometrías con el código {0} deben ser líneas.", entidad.Codes[0].Name));
		        return entidad;
        }
    }
}
```

