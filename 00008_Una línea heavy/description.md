Hacé el procedimiento `LineaEstePesada(peso, color, longitud)`.
Debe dibujar hacia el `Este` una línea del `color` dado, poniendo en cada celda tantas bolitas como indique el `peso`. La linea debe ser tan larga como la `longitud`. 

A modo de ejemplo, `LineaEstePesada(3, Verde, 5)` debería dibujar una línea verde, ocupando cinco celdas hacia el Este y poniendo tres bolitas en cada una de ellas:

<gs-board>
  GBB/1.0
  size 5 2
  cell 0 0 Verde 3 
  cell 1 0 Verde 3 
  cell 2 0 Verde 3
  cell 3 0 Verde 3
  cell 4 0 Verde 3
  head 0 0
</gs-board>

Tené en cuenta que el cabezal **debe regresar a la posición inicial**