# Referencia

Digi3D.NET es una aplicación mixta de Windows, lo que significa que parte de la aplicación es nativa y parte es administrada.

La parte administrada son una serie de ensamblados firmados digitalmente que se instalan en el GAC y que permiten a las aplicaciones .NET acceder a los servicios que proporciona el programa.

Para que un programa .NET pueda acceder a los tipos publicados por uno de estos ensamblados, deberá tener una referencia al ensamblado en sus metadatos.

La forma más sencilla de hacer referencia a los ensamblados que proporciona Digi3D.NET es mediante paquetes [NuGet](https://www.nuget.org/profiles/Digi21).

Al instalar cualquiera de estos paquetes NuGet lo que se instala es un [ensamblado de referencia](https://docs.microsoft.com/en-us/dotnet/standard/assembly/reference-assemblies) al ensamblado realmente instalado en el GAC. Una característica que tienen los ensamblados de referencia es que no se copian al destino al compilar nuestro programa, de manera que si hacemos un programa que se llame bintram.exe, copiando únicamente ese .exe podremos ejecutarlo en cualquier máquina que tenga instalado Digi3D.NET.

A continuación, el listado de paquetes NuGet:

* [Digi21.DigiNG](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/digi21.diging/)
* [Digi21.DigiNG.Plugin](/digi3d-net/programacion/.net/referencia/digi21.diging.plugin/)
* [Digi21.Utilities](/digi3d-net/programacion/.net/referencia/digi21.utilities.md)
* [Digi21.DigiNG.Topology](/digi3d-net/programacion/.net/referencia/digi21.diging.topology.md)
* [Digi21.OpenGis](/digi3d-net/programacion/.net/referencia/digi21.opengis.md)
* [Digi21.Epsg](/digi3d-net/programacion/.net/referencia/digi21.epsg.md)
* [Digi21.DigiNG.IO.Bin](/digi3d-net/programacion/.net/referencia/digi21.diging.io.bin/)
* [Digi21.DigiNG.IO.BinDouble](/digi3d-net/programacion/.net/referencia/digi21.diging.io.bindouble/)
* [Digi21.DigiNG.IO.Shp](/digi3d-net/programacion/.net/referencia/digi21.diging.io.shp/)
* [Digi21.DigiNG.IO.Geomedia](/digi3d-net/programacion/.net/referencia/digi21.diging.io.geomedia/)

