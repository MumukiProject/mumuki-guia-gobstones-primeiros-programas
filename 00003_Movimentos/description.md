Até agora o que você fez não foi tão emocionante assim. Isso porque não ensinamos como dar instruções para a máquina e apenas mostramos um tabuleiro. Nesse exercício vamos aprender uma das ordens que podemos dar para a máquina: mover a garra.

Por exemplo, a partir de um tabuleiro **inicial** vazio, podemos facilmente escrever um programa que mova a garra de uma determinada posição em direção ao **norte**.

| Inicial |   | Final |
|:-------:|:-:|:-----:|
|![3x3h](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h.png)|<i class="fa fa-arrow-right"></i>|![3x3h01](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/3x3h01.png)|

O **código** do programa (ou seja, o **texto** da descrição da solução do problema que daremos ao computador) que consegue isso é o seguinte:

``` gobstones
program {
  Mover(Norte)
}
```

> Não acredita? Então escreva o código anterior no editor e clique em Enviar.
