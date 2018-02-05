Até agora o que você fez não foi tão emocionante assim. Isso porque não ensinamos como dar instruções para a máquina e apenas mostramos um tabuleiro. Nesse exercício vamos aprender uma das ordens que podemos dar para a máquina: mover a garra.

Por exemplo, a partir de um tabuleiro **inicial** vazio, podemos facilmente escrever um programa que mova a garra de uma determinada posição em direção ao **norte**.

| Inicial |   | Final |
|:-------:|:-:|:-----:|
|<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>|<i class="fa fa-arrow-right"></i>|
<gs-board>
  GBB/1.0
    size 3 3
    head 0 1
</gs-board>|





O **código** do programa (ou seja, o **texto** da descrição da solução do problema que daremos ao computador) que consegue isso é o seguinte:

``` gobstones
program {
  Mover(Norte)
}
```

> Não acredita? Então escreva o código anterior no editor e clique em Enviar.

