# Archivo

[Ficha de herramientas Editar](/mdtopx/fichas-de-herramientas/ficha-de-herramientas-editar/)

En este epígrafe están agrupados los comandos relativos a la edición del documento activo:

* **Sumar archivo**: Une archivos existentes al actual. El programa abrirá el explorador de Windows para seleccionar los archivos a agregar. En este cuadro de diálogo se podrá seleccionar un solo archivo o varios, utilizando las teclas \[Mayúsculas\] y \[Control\]. La forma de actuar del programa diferirá en función del tipo de documento actual:
  * En el caso de tener activo un modelo digital, sólo se le podrán agregar archivos de este tipo. El programa retriangulará la nueva información para evitar inconsistencias del nuevo modelo digital resultante. Si existe solape entre los modelos el programa mostrará un [cuadro de diálogo](../../operaciones-con-archivos/agregar-modelos-digitales-del-terreno.md)con diferentes opciones de actuación.
  * En caso de tener activo un archivo de dibujo, se le podrán agregar archivos de dibujo BIN, DXF, DGN, ASC, PTS o LAS.
  * Si el documento es una imagen, no se podrán agregar archivos, por lo que el comando permanecerá desactivado. Para ello, se podría utilizar la herramienta [Unir imágenes](/mdtopx/herramientas-para-imagenes/unir-imagenes.md).
* \*\*\*\*[**Cargar referencia**](../../operaciones-con-archivos/abrir-archivos-de-referencia.md): Permite cargar archivos de referencia de diversos formatos sobre el documento actual. No se pueden referenciar archivos a un documento de imagen sin georreferenciación, por lo que, en esta circunstancia, la herramienta no estará activa.
* **Comprimir**: Esta herramienta permite analizar el documento actual eliminando definitivamente aquellas entidades que tuviesen marca de Borrado. En el caso de archivos de dibujo, estas marcas de borrado las tendrían las entidades de dibujo. En el caso de archivos de modelo digital, las marcas de borrado las podrían tener puntos o triángulos. En el caso de archivos de imagen, no hay posibilidad de marca de borrado por lo que esta herramienta permanecerá desactivada.
* \*\*\*\*[**Transforma coordenadas**](../../otras-herramientas/transformacion-de-coordenadas.md): Esta herramienta permite transformar las coordenadas de un documento de dibujo o de un documento de modelo digital mediante transformaciones Helmert 2D o 3D, Afín o utilizando una rejilla NTV2.
* **Copiar portapapeles**: Con esta herramienta se puede copiar el contenido de la vista actual al portapapeles de Windows en formato de imagen, dando la posibilidad de pegarlo en otro documento de otra aplicación
* \*\*\*\*[**Insertar hoja**](../../otras-herramientas/insertar-hoja.md): Herramienta para insertar un marco de hoja con canevás de coordenadas a un documento de dibujo.
* **División por hojas**: Bajo este icono están agrupadas dos herramientas relacionadas con las hojas cartográficas:
  * _División por hojas_: Esta herramienta permite generar nuevos archivos cortando el documento actual en función de coordenadas o entidades vectoriales almacenadas en un fichero. La herramienta presentará un cuadro de diálogo diferente en función de si el documento actual es un [modelo digital del terreno de tipo TIN](../../otras-herramientas/cortar-por-hojas.md)o un documento de [dibujo vectorial o una rejilla](../../otras-herramientas/division-por-hojas.md).
  * \_\_[_Gráfico de hojas_](../../otras-herramientas/grafico-de-hojas.md): Esta herramienta permite generar nuevos archivos cortando el documento actual según límites de hojas almacenados en un archivo de dibujo.
* **Salvar imagen actual**: Esta herramienta genera un nuevo documento imagen con la vista actual del documento activo. Es útil para salvar el documento y realizar documentaciones o presentaciones.
* **Extraer límites**: Mediante esta herramienta se pueden calcular los límites que ocupan un fichero o un determinado conjunto de puntos. En función de si el documento actual es un [dibujo vectorial genérico](../../otras-herramientas/extraer-limites.md)o un archivo con [nube de puntos](../../otras-herramientas/extraer-limites-lidar.md), el cuadro de diálogo presentado será diferente.
* **Borra en límites**: Esta herramienta permitirá borrar triángulos dentro o fuera de límites. El cuadro de diálogo mostrado será diferente en función de si el documento es un [modelo digital de tipo TIN o un archivo de dibujo](../../herramientas-de-edicion-de-la-triangulacion/borrar-fuera-o-dentro-de-limites.md), o si el documento es un [modelo digital basado en rejilla](../../modulo-virtualand/borra-en-limites.md).
* \*\*\*\*[**Base de datos**](../../otras-herramientas/editar-elementos/base-de-datos.md): Desde esta herramienta se puede gestionar la base de datos asociada al documento actual, mostrando su composición y atributos asociados.
