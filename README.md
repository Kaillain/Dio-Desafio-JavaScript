# Desafio-1-JORNADA HEROICA

<h1><b>Descrição</b></h1> 

 Você é um mestre construtor em um mundo de blocos e tem a tarefa de gerar biomas em diferentes regiões do mundo. Cada bioma tem características únicas, como tipos de solo, vegetação e clima.
 Tarefa: Sua tarefa é coletar minérios enquanto ataca uma rocha com sua picareta. Use loops e lógica de programação para representar cada golpe na rocha e determinar qual minério foi obtido.

<h1><b> Entrada</b></h1> 
O programa irá solicitar que você digite um número inteiro positivo representando a quantidade de golpes que você deseja dar com a picareta.

<h1><b>Saída</b></h1> 
 Para cada golpe que você der, o programa exibirá uma mensagem indicando o resultado do golpe. Será mostrado o número do golpe e o minério obtido, que pode ser Pedra, Carvao, Ferro ou Diamante.

<h1><b>Conceitos Aprendidos com o Desafio:</b></h1> 

 Nesse desafio "Geração de Biomas em um Mundo de Blocos", você aprendeu e utilizou os seguintes conceitos de programação:

 Variáveis e Tipos de Dados: Você declarou uma variável chamada quantidadeGolpes para armazenar o número de golpes que serão dados com a picareta. Utilizou a função parseInt() para converter a entrada do usuário em um número inteiro.

Arrays (Matrizes): Você criou um array chamado minerais que armazena os diferentes tipos de minerais que podem ser obtidos após cada golpe. Cada mineral é representado como uma string.

 Estruturas de Repetição (Loops): Utilizou um loop for para simular os golpes com a picareta. O loop percorre de 1 até a quantidade de golpes desejada, representada por i. Isso permite que você execute a mesma ação repetidamente.

Operadores Matemáticos: Usou o operador de módulo (%) para calcular o índice do mineral a ser obtido após cada golpe. Isso garante que o índice não ultrapasse o comprimento do array minerais, permitindo que o ciclo se repita.

Concatenação de Strings: Utilizou a concatenação (símbolo de +) de strings para criar a mensagem de saída exibida após cada golpe. Isso envolveu a combinação do número do golpe (i), o texto estático e o mineral obtido a partir do array minerais.

<h1><b>Código</b></h1>

Desafios JavaScript na DIO têm funções "gets" e "print" acessíveis globalmente:
//- "gets" : lê UMA linha com dado(s) de entrada (inputs) do usuário;

// - "print": imprime um texto de saída (output), pulando linha.

//Lê a quantidade de golpes informada pelo usuário.
// O parseInt(()) vai converter os valores de entrada(string) para um valor numérico(Int).
//const quantidadeGolpes = parseInt(gets());

// TODO: Defina aqui os tipos de minerais Pedra, Carvao, Ferro, Diamante
let minerais = ["Pedra", "Carvao", "Ferro", "Diamante"];

 //Loop para cada golpe, de 1 até a quantidade informada
for (let i = 1; i <= quantidadeGolpes; i++) {

  //Calcula o índice do mineral usando o operador de módulo (%) para garantir que o índice esteja dentro do tamanho do array
  let minaIndex = i % minerais.length;

 //TODO: Agora exiba o índice i, concatene com o caractere ":", após, concatene com tipo de minerais[minaIndex]:
   print(i + ": " + minerais[minaIndex]);
}
