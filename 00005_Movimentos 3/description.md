Como deve imaginar a garra não se move apenas em direção ao norte, e um programa pode combinar quaisquer tipos de movimentos

> Escreva um programa que mova a garra duas posições em direção ao Leste e uma posição em direção ao Sul, produzindo o seguinte efeito:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 3 3
        head 0 2
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 3 3
        head 2 1
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
     
Lembre que o comando que move a garra se chama  `Mover` (não deve escrever `mOvEr`, `mover` ou `MOVER`). **É importantíssimo respeitar a sintaxe!** Se você não respeita, o programa não funcionará: _buuuu_ :fearful:.