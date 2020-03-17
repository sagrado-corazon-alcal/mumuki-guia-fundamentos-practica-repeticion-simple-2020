En la guía anterior, vimos que se podía usar `repeat` para hacer algo muchas veces. Hicimos un ejemplo que se llamaba `Diagonal4Azul`, que era más o menos así:

```gobstones
procedure Diagonal4Azul(){
    repeat(4){
        Poner(Azul)
        Mover(Este)
        Mover(Norte)
    }
}
```

¿Te animás a definir el procedimiento `Diagonal4AzulVolviendo`? Este procedimiento debería _hacer lo mismo_ que `Diagonal4Azul`, pero tiene que dejar el cabezal **en la posición inicial**.

<gs-board>
  GBB/1.0
   size 4 4
   cell 0 0 Azul 1 
   cell 1 1 Azul 1 
   cell 2 2 Azul 1 
   cell 3 3 Azul 1 
   head 0 0
</gs-board>

**¡Ojo!** No vale volver a escribir el código que ya escribiste en la guía pasada. ¡No hay que repetir código!
Entonces, podés usar `Diagonal4Azul()` sin definirlo. :wink:
