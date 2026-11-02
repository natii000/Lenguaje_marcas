1. static

El cuadro 1 no se mueve al añadir left: 50px, porque static es la posición normal y no deja mover el elemento con left, right, top o bottom.

2. relative

El cuadro 2 se mueve 20px hacia abajo y 50px hacia la derecha. Conserva su espacio original, por lo que deja un hueco donde estaba antes.

3. absolute

El cuadro 3 se coloca en la esquina superior derecha del contenedor, porque este tiene position: relative.

El cuadro 3 sale del recuadro y no deja hueco. Los demás cuadros ocupan su espacio habitual.

4. z-index

El cuadro 2 sube 40px y se solapa con el cuadro 1. El cuadro 1 queda por encima porque tiene z-index: 2, mientras que el cuadro 2 tiene z-index: 1.

z-index permite controlar qué elemento aparece delante cuando hay solapamiento.