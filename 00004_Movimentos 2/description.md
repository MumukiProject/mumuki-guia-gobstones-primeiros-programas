Vamos entender o que acabamos de fazer: escrever um programa.

Todo programa tem exatamente um `program`: uma parte do código que ordena os comandos (ações) que queremos que a máquina realize sobre o tabuleiro **inicial**. Ao **executar** um programa obteremos um tabuleiro **final**.

A sintaxe de um `program` é bem simples:
 
1. Escrevemos uma linha horizontal que diga `program`, seguida de uma chave de abertura: `{`
2. Em seguida, os comandos: um por linha
3. E finalmente, uma última chave que fecha a que abrimos anteriormente `}`

Alguns exemplos de `program`s:

```gobstones
program {
}
```

(Não faz nada)

```gobstones
program {
  Mover(Norte)
}
```

(Move a garra de uma determinada posição em direção ao norte)

```gobstones
program {
  Mover(Norte)
  Mover(Norte)
}
```

(Move a garra duas posições em direção ao norte)

> Sabendo disso, escreva um programa que em um tabuleiro de 2x4 com a garra na origem (a célula de baixo no lado esquerdo), mova a garra três vezes em direção ao norte:

| Inicial |   | Final |
|:-------:|:-:|:-----:|
|![2x4h00](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/2x4h00.png)|<i class="fa fa-arrow-right"></i>|![2x4h03](https://raw.githubusercontent.com/sagrado-corazon-alcal/mumuki-fundamentos-gobstones-guia-1-primeros-programas/master/2x4h03.png)|

