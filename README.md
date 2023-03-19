Jogo da Velha em Python
Este é um programa simples em Python que permite que dois jogadores joguem o clássico jogo da velha. O programa usa uma interface de linha de comando para solicitar que os jogadores façam suas jogadas.

Como Jogar
Para jogar o jogo da velha, basta executar o arquivo jogo_da_velha.py em um terminal ou prompt de comando. O tabuleiro será exibido e você será solicitado a digitar as coordenadas da posição em que deseja fazer sua jogada.

As coordenadas são digitadas no formato linha,coluna. Por exemplo, para fazer uma jogada na primeira linha e segunda coluna, digite 1,2.

O primeiro jogador é representado pelo símbolo "X" e o segundo jogador é representado pelo símbolo "O". O objetivo do jogo é fazer uma linha, coluna ou diagonal com três símbolos iguais antes do seu oponente.

Exemplo de Jogo

   |   |   
---|---|---
   |   |   
---|---|---
   |   |   

Jogador 1 (X), faça sua jogada: 1,1

 X |   |   
---|---|---
   |   |   
---|---|---
   |   |   

Jogador 2 (O), faça sua jogada: 2,2

 X |   |   
---|---|---
   | O |   
---|---|---
   |   |   

Jogador 1 (X), faça sua jogada: 1,2

 X | X |   
---|---|---
   | O |   
---|---|---
   |   |   

Jogador 2 (O), faça sua jogada: 2,1

 X | X |   
---|---|---
 O | O |   
---|---|---
   |   |   

Jogador 1 (X), faça sua jogada: 3,1

 X | X |   
---|---|---
 O | O |   
---|---|---
 X |   |   

Parabéns, Jogador 1 (X)! Você ganhou!
