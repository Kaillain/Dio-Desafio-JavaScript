# Desafio-5-A jORNADA hEROICA

<h1><b>Descrição</b></h1> 

Você é um jovem herói que embarca em uma jornada épica para derrotar o temido dragão que aterroriza o reino. No entanto, você precisa atravessar uma floresta perigosa para chegar à caverna do dragão. Cada passo é crucial, e sua jornada será determinada pela lógica afiada que você possuir.


<h1><b>Tarefa</b></h1> 
Escreva um algoritmo que simule a jornada do herói pela floresta. O herói começa em uma posição inicial e deve dar uma série de passos para atravessar a floresta até a caverna do dragão.


<h1><b> Entrada</b></h1> 
A posição inicial do herói na floresta (um número inteiro).

O número total de passos que o herói deve dar (um número inteiro).


<h1><b>Saída</b></h1> 

Imprima a posição final do herói após dar a quantidade de passos especificada.

<h1><b>Código</b></h1>

const posicaoInicial = parseInt(gets());

const totalPassos = parseInt(gets());

const posicaoFinal = posicaoInicial +  totalPassos;

print("Posicao final do heroi:", posicaoFinal);
