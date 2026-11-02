Diferencia entre sticky y fixed

position: sticky: el menú es como un elemento normal hasta que llega a la parte superior de la pantalla. En ese momento se queda pegado mientras se desplaza la página.

position: fixed: el menú se queda siempre en la misma posición de la pantalla, independientemente del movimiento. Sale del flujo normal y el contenido que tenía debajo puede ocupar su lugar, quedando tapado por el menú.

El menú utiliza top: 0 para quedarse pegado arriba y z-index: 10 para aparecer por delante del contenido.

El botón «Subir» utiliza position: fixed para permanecer en la esquina inferior derecha de la pantalla.