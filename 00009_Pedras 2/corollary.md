Note que neste problema, se mudamos a ordem em que _chamamos_ (usamos o) `Colocar`, o resultado não muda: sempre terminará com um tabuleiro com três pedras vermelhas, uma azul e uma verde.

Por exemplo, os dois seguintes programas também resolvem esse mesmo problema:

``` gobstones
program {
  Colocar(Vermelho)
  Colocar(Vermelho)
  Colocar(Vermelho)
  Colocar(Verde)
  Colocar(Azul)
}
```

``` gobstones
program {
  Colocar(Vermelho)
  Colocar(Azul)
  Colocar(Vermelho)
  Colocar(Verde)
  Colocar(Vermelho)
}
```
