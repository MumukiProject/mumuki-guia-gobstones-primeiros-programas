Como percebeu no exercício anterior, o tabuleiro criado tinha uma **célula** marcada:

<gs-board>
  GBB/1.0
    size 3 3
    head 0 0
</gs-board>

Por que isso acontece? Porque nossa máquina tem uma **garra**, que sempre estará situada sobre uma das células do tabuleiro e pode realizar diferentes operações sobre a célula (paciência que já as conheceremos :grin:).

Por exemplo, a próxima figura é um tabuleiro de 5x2, com a garra na segunda fila e na quarta coluna.

<gs-board>
  GBB/1.0
    size 5 2
    head 3 1
</gs-board>

Algo importante: contamos as fileiras de baixo para cima, e as colunas da esquerda para a direita. A primeira **fileira** é a que está **abaixo** de tudo, e a primeira **coluna** é a do lado **esquerdo**.

> Ainda não se convenceu? Então pressione o botão Enviar e criaremos um tabuleiro de 3x3 com a garra na segunda coluna e na terceira fileira.
