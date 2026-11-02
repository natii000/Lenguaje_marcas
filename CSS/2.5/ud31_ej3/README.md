Parte A:
La tarjeta tiene position: relative para que la etiqueta con position: absolute se coloque respecto a ella.

La etiqueta se desplaza 10px hacia arriba y 10px hacia la derecha, por lo que sobresale de la tarjeta.

Si ponemos overflow: hidden en la tarjeta, la parte de la etiqueta que sobresale queda cortada. Para solucionarlo, podemos quitar esa propiedad o colocar la etiqueta dentro de un contenedor que no recorte su contenido.

Parte B: Caja de comentarios

overflow: visible: el contenido que no cabe sobresale de la caja.

overflow: hidden: el contenido que no cabe queda oculto.

overflow: scroll: aparecen barras de desplazamiento para poder consultar el contenido.

overflow: auto: aparecen barras de desplazamiento cuando son necesarias.

La caja de comentarios se deja con overflow: auto.

Diferencia entre visibility y display

visibility: hidden: el elemento desaparece visualmente, pero conserva el espacio que ocupaba.

display: none: el elemento desaparece y deja de ocupar espacio en la página. Los elementos siguientes se colocan en el espacio que queda libre.