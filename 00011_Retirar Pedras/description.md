Da mesma maneira que tem um “colocar pedra” (`Colocar`), temos um “retirar pedra” (`Retirar`), que tira exatamente uma peça da cor dada.

Por exemplo, o seguinte programa retira duas pedras da posição inicial.

``` gobstones
program {
  Retirar(Vermelho)
  Retirar(Vermelho)
}
```

> Sabendo disso, escreva um programa que elimine **apenas** a pedra vermelha desse tabuleiro. Tenha cuidado! Preste atenção a posição da garra! :wink:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>
