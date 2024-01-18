# Desafio-3-COLETANDO TESOUROS

<h1><b>Descrição</b></h1> 

Sua missão é vasculhar as salas da masmorra em busca de recompensas lendárias e desafios perigosos. Cada sala pode conter monstros formidáveis, tesouros preciosos ou ambos. Use suas habilidades estratégicas para enfrentar as ameaças e coletar os tesouros!


<h1><b>Tarefa</b></h1> 
Escreva um programa que simule sua jornada heróica pela masmorra. O programa deve percorrer cada sala e verificar se há tesouros ou monstros. Se você encontrar um tesouro, colecionará a recompensa. Se encontrar um monstro, terá que derrotá-lo para continuar.

<h1><b> Atenção</b></h1> 
Em nossa resolução utilizamos a função.includes() do JavaScript para verificar se um número (representando a sala atual) está presente nos arrays salasComTesouro e salasComMonstro.
 
<h1><b> Entrada</b></h1> 
O número total de salas no dungeon (um número inteiro).

<h1><b>Saída</b></h1> 
empre que encontrar um tesouro, imprima " Tesouro na sala X!".

Sempre que encontrar um monstro, imprima "Monstro na sala X!".

<h1><b>Código</b></h1>


   const salasComTesouro = [2, 4, 7];
   
   const salasComMonstro = [3, 6, 8];
   
for (let sala = 1; sala <= totalSalas; sala++)

{ 
    const temTesouro = salasComTesouro.includes(sala);
    
    const temMonstro = salasComMonstro.includes(sala);
    
    if (temTesouro ) 
    
    {
    
        print("Tesouro na sala " + sala + "!");
        
    }
    
    else if ( temMonstro )
    
    {
    
        print("Monstro na sala " + sala + "!");
        
    }
} 
