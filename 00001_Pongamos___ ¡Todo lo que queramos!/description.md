Ahora que tenemos una idea de _reutilización_, y practicamos _repetición_, vamos a definir un procedimiento **que nos va a servir de acá en adelante**.

Necesitamos un procedimiento que nos ayude a poner muchas bolitas. Sí, podríamos simplemente usar un `repeat` para lograrlo, pero como es una tarea re-común que vamos a hacer un montón de veces, vamos a preferir definir un `procedure` llamado `PonerN`. Nuestro procedimiento debe poner la cantidad de bolitas indicada de un color dado.

Por ejemplo, `PonerN(3, Azul)` haría esto:

<gs-board>   
  GBB/1.0
  size 2 2
  cell 0 0 Azul 3
  head 0 0
<gs-board>

> Definí el procedimiento `PonerN(cantidad, color)`.