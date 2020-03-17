_¡Ya sabés Kung Fu!_

Ahora, tenés que mostrarnos que podés _dibujar un reloj_. Lo que haremos por ahora es solamente poner los números que aparecen en un típico reloj de agujas: 

* El 12 arriba,
* El 3 a la derecha,
* El 9 a la izquierda, y
* el 6 abajo.

> Hacer un procedimiento `DibujarReloj(radio)`, que ponga los números del reloj como se indica arriba, **alrededor del casillero actual**. El tamaño del reloj se indica con el `radio` que recibís por parámetro: mientras más grande es el radio, más alejados están los números del centro.

Dado el siguiente program:

```gobstones
program {
  DibujarReloj(2)
}
```

El reloj resultante es así:

<gs-board>
  GBB/1.0
    size 5 5
    cell 0 2 Rojo 9 
    cell 2 0 Rojo 6 
    cell 4 2 Rojo 3 
    cell 2 4 Rojo 12 
    head 2 2
</gs-board>