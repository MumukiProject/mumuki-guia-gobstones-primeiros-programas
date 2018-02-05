Algo interessante de nossos tabuleiros é que nas suas células podemos colocar qualquer quantidade de pedras e de qualquer cor. 

Por exemplo, se temos este tabuleiro:

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>

e executamos o seguinte programa:

``` gobstones
program {
  Colocar(Vermelho)
  Colocar(Vermelho)
  Colocar(Azul)
  Colocar(Verde)
  Colocar(Vermelho)
}
```

A garra colocará na célula atual três pedras vermelhas, uma azul e uma verde.

> Escreva esse programa no editor e veja como fica o tabuleiro!
