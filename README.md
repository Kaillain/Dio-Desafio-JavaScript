# Desafio-3-CAPTURANDO POKEMON 

<h1><b>Descrição</b></h1> 

 No mundo dos jogos Pokémon, os treinadores começam sua jornada escolhendo um dos três Pokémons iniciais: Bulbasaur, Charmander e Mewtwo. Cada treinador escolhe um dos quatro pokemons. 
 Seu desafio é criar uma solução que permita ao jogador escolher um dos Pokémons iniciais e exibir uma mensagem de boas-vindas e o Pokémon escolhido.
 
<h1><b> Entrada</b></h1> 
Você receberá um número inteiro que representa a escolha do treinador: 1 para Bulbasaur, 2 para Charmander, 4 Pikachu e 5 para Mewtwo.

<h1><b>Saída</b></h1> 
A saída deve ser uma mensagem de boas-vindas que inclua o nome do Pokémon escolhido.

<h1><b>Código</b></h1>
//Desafios JavaScript na DIO têm funções "gets" e "print" acessíveis globalmente:
  
//- "gets" : lê UMA linha com dado(s) de entrada (inputs) do usuário;

//- "print": imprime um texto de saída (output), pulando linha.

// Entrada de dados. Lembre-se: O parseInt(()) é importante para a conversão dos valores de entrada(String) para um valor numérico(int).

<b>let escolhaDoTreinador = parseInt(gets());
let pokemonEscolhido; </b>

//TODO: Implemente as condições necessárias para a solução do desafio. Utilize a tabela de exemplos para identificar a escolha do treinador:
<b>

if ( escolhaDoTreinador === 1) {

    pokemonEscolhido = "Bulbasaur";
} else if ( escolhaDoTreinador === 2 ) {

    pokemonEscolhido = "Charmander";
} else if ( escolhaDoTreinador === 4 ) {

    pokemonEscolhido = "Pikachu";
} else{

    pokemonEscolhido = "Mewtwo";
}
</b>

//Imprime o Pokémon escolhido:
<b>

if (pokemonEscolhido) {

    print("Voce escolheu o " + pokemonEscolhido + " como seu Pokemon inicial.");
}
</b>
