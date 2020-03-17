Muchas veces vamos a usar el tablero de Gobstones como memoria, o sea, para recordar algo importante que vamos a necesitar más adelante. 

¿Qué podríamos representar con bolitas? Por ejemplo una fecha. Una fecha que debemos recordar es el _24 de Marzo de 1976_, hoy constituido [Día de la Memoria por la Verdad y la Justicia](https://es.wikipedia.org/wiki/D%C3%ADa_Nacional_de_la_Memoria_por_la_Verdad_y_la_Justicia) en Argentina.

El objetivo, entonces, es hacer un procedimiento `DiaDeLaMemoria()`:

* En la celda actual, poné 24 bolitas Azules, que **representan** el día.
* En la celda inmediatamente al Este, poné 3 bolitas Verdes, que **representan** el mes.
* En la celda a continuación, poné 1976 bolitas Negras, **representando** el año.

<gs-board>
  GBB/1.0
  size 3 1
  cell 0 0 Azul 24 
  cell 1 0 Verde 3 
  cell 2 0 Negro 1976
  head 2 0
</gs-board>
