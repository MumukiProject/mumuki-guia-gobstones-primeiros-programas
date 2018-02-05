Ótimo, você já entendeu como mover a garra do tabuleiro utilizando a operação `Mover` e as direções (`Sul`, `Oeste`, etc.). Vamos adiante com um passo mais: as **pedras**.

Em qualquer célula do nosso tabuleiro podemos colocar `pedras`. Elas existem com diferentes cores:

* Vermelhas (`Vermelho`)
* Azuis (`Azul`)
* Pretas (`Preto`)
* E verdes (`Verde`)

Por exemplo, este é um tabuleiro com uma pedra vermelha e uma preta:

<gs-board>
  GBB/1.0
    size 2 2
    cell 1 0 Rojo 1
    cell 1 1 Negro 1
    head 1 1
</gs-board>

Além de se mover, a garra também pode colocar pedras na **célula atual**. Para isso contamos com a operação `Colocar`, que diz à garra que deposite uma pedra com a cor dada:

``` gobstones
program {
  Colocar(Vermelho)    
}
```

> Experimente esse programa! Escreva o código no editor, envie e veja o que acontece quando executa o código sobre este tabuleiro:

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>