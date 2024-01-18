# Desafio-2-PONTUANDO EXPERIÊNCIA - XP 

<h1><b>Descrição</b></h1> 

 Você é um herói em mundo mágico repleto de monstros e desafios.
 Sua missão agora é enfrentar inimigos e ganhar pontos de experiência (XP) para se tornar mais forte. 
 A cada vitória, você ganha XP e se aproxima de se se tornar um lendário campeão.

 <h1><b>Tarefa</b></h1>
  Escreva um programa simples que simule o ganho de XP após derrotar um monstro. O programa deve calcular e exibir a quantidade de XP com base no nível do monstro e a dificuldade da batalha.

  <h1><b>Calculo de XP</b></h1>
  Para calcular a quantidade de XP ganhos, o programa precisa considerar o nível do monstro e a dificuldade da batalha. A fórmula num1 * num2 * 100 é usada para calcular essa quantidade com base nos valores fornecidos.

  <h1><b>Explicação:</b></h1>
  num1: Este é o nível do monstro. Quanto maior o nível do monstro, mais XP você ganhará ao derrotá-lo. Portanto, multiplicar o nível do monstro por um valor maior ajudará a refletir o aumento da recompensa de XP para monstros mais poderosos.

  num2: Este é o valor da dificuldade da batalha, variando de 1 a 100. Quanto maior a dificuldade da batalha, mais XP você deve ganhar para enfrentar um desafio maior. Multiplicar pela dificuldade ajuda a ajustar a recompensa de XP com base na intensidade da batalha.

 100: Este é o multiplicador constante que determina a escala geral de recompensa de XP. Multiplicar pelo nível do monstro e pela dificuldade aumenta a recompensa em 100 vezes o valor do nível e da dificuldade.

<h1><b> Entrada</b></h1> 
O nível do monstro (um número inteiro).

A dificuldade da batalha, representada por um valor de 1 a 100 (um número inteiro).

<h1><b>Saída</b></h1> 
 Imprima a quantidade de XP ganhos após a batalha.

<h1><b>Código</b></h1>

//Desafios JavaScript na DIO têm funções "gets" e "print" acessíveis globalmente:

//- "gets" : lê UMA linha com dado(s) de entrada (inputs) do usuário;

//- "print": imprime um texto de saída (output), pulando linha.

// Entrada de dados. Lembre-se: O parseInt(()) é importante para a conversão dos valores de entrada(String) para um valor numérico(int).

<b>let num1 = parseInt(gets());
let num2 = parseInt(gets()); </b>

//TODO: Implemente a lógica para exibir o xpGanho:

<b>const xpGanho = num1*num2*100;</b>

// Imprime a quantidade de XP ganho

<b>print("Voce ganhou " + xpGanho + " XP!");</b>
