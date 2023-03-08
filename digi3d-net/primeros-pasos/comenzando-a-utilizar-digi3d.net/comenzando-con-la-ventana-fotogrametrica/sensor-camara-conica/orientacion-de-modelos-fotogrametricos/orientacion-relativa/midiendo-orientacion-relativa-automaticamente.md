# Midiendo la orientación relativa automáticamente

Digi3D.NET puede medir la orientación relativa automáticamente mediante algoritmos de [correlación](midiendo-orientacion-relativa-automaticamente.md), de manera que no será necesario medir ningún punto para realizar la orientación relativa.

El programa medirá puntos homólogos automáticamente. Al ser un proceso completamente automático es posible que algún punto no se mida correctamente. La manera de solucionar este problema es medir muchos más puntos \(cuando seguiste los pasos de [Midiendo la orientación relativa manualmente](/digi3d-net/primeros-pasos/comenzando-a-utilizar-digi3d.net/comenzando-con-la-ventana-fotogrametrica/sensor-camara-conica/orientacion-de-modelos-fotogrametricos/orientacion-relativa/midiendo-orientacion-relativa-manualmente.md), asumir que un pequeño porcentaje de estos puntos estará medido de manera incorrecta y calcular la orientación relativa teniendo en cuenta esto precisamente, que algún punto no estará medido correctamente. El cálculo de la orientación relativa de Digi3D.NET utiliza _estimadores robustos_, y gracias a ellos se detectan estos puntos mal medidos y el resultado final es que no se tienen en consideración, obteniendo una orientación relativa perfecta.

Es necesario que finalices los pasos de [Archivos de orientación relativa](/digi3d-net/primeros-pasos/comenzando-a-utilizar-digi3d.net/comenzando-con-la-ventana-fotogrametrica/sensor-camara-conica/orientacion-de-modelos-fotogrametricos/orientacion-relativa/archivos-orientacion-relativa.md) antes de ejecutar los siguientes pasos para medir una orientación relativa automáticamente:

1. Pulsa el botón **R** de la barra de herramientas de la ventana fotogramétrica.
2. Comprueba que en la barra de mensajes aparece una barra de progreso indicando que se está calculando el recubrimiento de las imágenes.
3. Si todo ha ido bien, deberías ver ambas imágenes en la misma posición.
4. Aparecerá el panel **Orientación relativa**.
5. En la parte inferior del panel **Orientación relativa** se muestra un texto indicándote que digitalices el punto 1 en la imagen izquierda.
6. Pulsa el botón **Correlar todo.** Aparecerá el cuadro de diálogo [Orientación Relativa Automática por Correlación](/digi3d-net/referencia/cuadros-de-dialogo/orientacion-relativa-automatica-por-correlacion.md)**.**
7. Pulsa el botón **Comenzar.** Comprueba cómo en la barra de estado aparece una barra de progreso indicando el progreso de la corralción.
8. Una vez finalizado comprueba que la lista de puntos medidos se ha rellenado con todas las medidas.
9. Digi3D.NET habrá ordenado los seis primeros puntos para que el primero sea el mejor de la primera zona de _Von Gruber_, el segundo el mejor de la segunda zona de _Von Gruber_, ... y el sexto el mejor de la sexta zona de _Von Gruber_. El resto de puntos aparecerán en el orden de correlación, es decir, primero aparecerán todos los medidos en la primera zona de _Von Gruber_, luego los de la segunda zona, y así sucesivamente.
10. Comprueba que no tienes paralaje por el modelo.
11. Pulsa el botón **Aceptar**.

## Vídeo

<video controls><source src="https://digi21.blob.core.windows.net/videos-ayuda/Midiendo%20la%20orientacion%20relativa%20automaticamente.mp4" caption="" type="video/mp4"></video>

