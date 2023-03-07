# Elementos

[Ficha de herramientas Editar](./)

En este epígrafe están agrupados los comandos relativos a la edición de elementos del documento activo:

* **Línea nueva**: Herramienta para introducir líneas en un documento de dibujo. Para introducir la nueva línea se deberá ir seleccionando los puntos que la componen con el botón izquierdo del ratón. Si se desea seleccionar un punto existente en el fichero, se deberá pulsar la tecla MAYÚSCULAS al mismo tiempo que se pulsa el botón izquierdo del ratón. Para eliminar un punto recién introducido se podrá pulsar la tecla Retroceso. Pulsando el botón derecho del ratón se terminará de introducir la línea y se mostrará un [cuadro de diálogo](../../otras-herramientas/editar-elementos/untitled-132.md) con la información de la nueva línea. Aceptando la información se almacenará la nueva línea en el fichero.
* **Punto nuevo**:
* **Texto nuevo**: Herramienta para introducir textos en un documento de dibujo. Para introducir el nuevo texto se deberá pulsar con el botón izquierdo del ratón sobre la ubicación elegida. A continuación, se mostrará un [cuadro de diálogo ](../../otras-herramientas/editar-elementos/untitled-135.md)con la información del nuevo texto. Aceptando la información se almacenará el nuevo texto en el fichero.
* **Medir**: Herramienta medir la distancia entre puntos indicados en pantalla. La información parcial se va mostrando en la [barra de estado ](../../introduccion/untitled-5.md)del programa, mostrando los incrementos de coordenadas. Los puntos se irán seleccionando con el botón izquierdo del ratón y se finalizará pulsando el botón derecho del ratón. Al finalizar se mostrará la distancia total medida en el [panel de Resultados](../../introduccion/untitled-303/untitled-302.md).
* **Información**: Herramienta para ofrecer información acerca del elemento seleccionado, ya sea perteneciente a un [dibujo ](../../otras-herramientas/editar-elementos/untitled-132.md)o un [triángulo](../../otras-herramientas/editar-elementos/untitled-136.md). Con el botón de la izquierda se selecciona el elemento deseado y se acepta y con el botón de la derecha se deselecciona o se intenta buscar otro elemento en la misma localización. También se puede deseleccionar pulsando la tecla \[ESC\].
* **Borrar**: Con esta opción se pueden borrar elementos de un dibujo o triángulos. En el caso de que el documento activo sea un modelo digital, se podrán borrar varios triángulos a la vez pulsando el botón izquierdo del ratón y arrastrando éste sin soltar describiendo una recta; todos los triángulos atravesados por dicha recta serán borrados. Una vez que se han seleccionado los elementos a borrar se puede proceder pulsando nuevamente el botón izquierdo del ratón o rechazar la selección pulsando el botón derecho o la tecla \[ESC\]. Esta herramienta puede ser seleccionada pulsando la tecla \[SUPR\].
* **Seleccionar**: Este comando muestra un menú donde se puede elegir la forma de seleccionar elementos gráficamente. Cada vez que se realice una nueva selección, se descartará la selección actualmente activa, excepto si se mantiene pulsada la tecla mayúscula durante la selección. Las opciones posibles son las siguientes:
  * **Mediante ventana rectangular**: Permite la selección de elementos describiendo una ventana rectangular definida por una de sus diagonales
  * **Mediante ventana circular**: Permite la selección de elementos describiendo un círculo definido por su centro y el radio
  * **Mediante ventana irregular**: Permite la selección de elementos describiendo una entidad cerrada definida por sus vértices. Los vértices se indicarán con el botón izquierdo del ratón y se finalizará con el botón derecho
  * **Desde archivo**: Permite la selección de elementos que están dentro de entidades cerradas que se encuentren almacenadas en un fichero con geometría vectorial. Al ejecutar el comando, el programa abrirá el explorador de Windows para que se elija el documento desde donde leer las geometrías.
  * **Invertir selección**: Una vez que se ha realizado una selección de elementos, el programa permite invertir ésta, seleccionando los elementos no seleccionados anteriormente y viceversa
* \*\*\*\*[**Cambia código**](../../otras-herramientas/editar-elementos/untitled-56.md): Esta herramienta permite cambiar masivamente un código de dibujo por otro. Sólo estará activa si el documento actual es un modelo digital o un dibujo.
* \*\*\*\*[**Seleccionar código**](../../otras-herramientas/editar-elementos/untitled-191.md): Con esta herramienta se puede generar un nuevo documento de dibujo con las entidades de los códigos seleccionados.
* **Unir todos**: Esta herramienta permite unir todas las entidades de dibujo que están conectadas en alguno de sus extremos, generando una entidad continua única. Sólo estará activa si el documento actual es un dibujo. Para que el programa pueda unir dos entidades se tienen que cumplir las siguientes condiciones:
  * Que las dos entidades tengan el mismo código.
  * Que las entidades tengan en común al menos uno de sus extremos.
  * Que no haya ninguna otra entidad que también tenga en común el extremo de unión.
* **Unir manual**: Esta herramienta permite unir entidades de dibujo que están conectadas en alguno de sus extremos, generando una entidad continua única. Sólo estará activa si el documento actual es un dibujo. Para que el programa pueda unir dos entidades se tienen que cumplir las mismas condiciones que en la unión automática de todo el fichero.
* \*\*\*\*[**Generaliza**](../../otras-herramientas/editar-elementos/untitled-112.md): Esta herramienta permite generalizar tanto lineal como superficialmente las entidades gráficas de un documento de dibujo, es decir, eliminar puntos innecesarios para su definición geométrica a una determinada escala. Por tanto, sólo estará activa si el documento actual es un dibujo.
* **Editar línea**: Esta herramienta permite editar gráficamente una entidad lineal. Se deberá seleccionar la línea mediante el botón izquierdo del ratón. Una vez iluminada la entidad requerida, se podrá pulsar con el botón izquierdo del ratón sobre el punto que se desea editar. El punto se iluminará igualmente y el usuario podrá moverlo gráficamente pulsando con el botón izquierdo del ratón y, sin soltarlo, mover el ratón. Estando seleccionado el punto, el usuario podrá eliminarlo pulsando la tecla \[SUPR\]. Asimismo, podrá insertar puntos nuevos sobre la posición del ratón actual, pulsando la tecla \[INS\]. Se saldrá de la edición, pulsando el botón derecho o la tecla \[ESC\].
* **Mover entidad**: Esta herramienta permite mover gráficamente una entidad. Se deberá seleccionar la entidad mediante el botón izquierdo del ratón. Una vez iluminada la entidad requerida, el usuario podrá moverla gráficamente pulsando con el botón izquierdo del ratón y, sin soltarlo, mover el ratón. Se saldrá de la edición, pulsando el botón derecho o la tecla \[ESC\].
* \*\*\*\*[**Paralela**](../../otras-herramientas/editar-elementos/untitled-166.md): Mediante esta herramienta es posible generar entidades paralelas de una línea

En esta ficha de herramientas existen comandos adicionales que no se muestran pero que puede ser agregados a la [barra de herramientas de acceso rápido ](../../untitled-12/untitled-6.md)o ser llamados mediante [teclas rápidas asociadas ](../../introduccion/untitled-324.md)y que son:

* **Deshacer**: Este comando sirve para deshacer la última modificación realizada sobre el documento actual. La tecla asociada es \[CTRL\]+\[Z\].
* **Rehacer**: Este comando sirve para rehacer la última operación deshecha sobre el documento actual. La tecla asociada es \[CTRL\]+\[Y\].
