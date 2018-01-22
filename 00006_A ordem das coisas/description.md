Quando trabalhamos com Gobstones, fazemos as coisas com uma certa ordem. Por exemplo, se temos este programa:

``` gobstones
program {
  Mover(Norte)
  Mover(Leste)
}
```

Uma possível maneira de ler este programa (conhecida como **operacional**) é como uma máquina faria, em ordem, de cima para baixo:

1.	Primeiro se move para o norte: `Mover(Norte)`
2.	Em seguida se move ao leste: `Mover(Leste)`

E de fato **se executa dessa maneira**. Isso é _como_ é feito.

No entanto, nós humanos somos melhores referindo-se especialmente ao resultado final: o objetivo do programa, isto é, o _que_ ele faz. E se pensamos assim (**denotacionalmente**) o que faz é: **move a garra para o nordeste**.

Por isso, existem várias maneiras de resolver um mesmo problema: podemos escrever vários programas que façam o mesmo (o _que_), mas que façam isso de maneiras diferentes (o _como_).

> Vamos ver se você entendeu isso: escreva outro programa que faça o mesmo que o de cima ( mover em direção ao nordeste), mas de maneira diferente. **Fique de olho:** deve funcionar em um tabuleiro de 2x2.