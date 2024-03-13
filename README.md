# Contadores

Esse repositório tem 3 contadores simples:
<ul>
    <li> Ficha RPG</li>
    <li> Formulário Formatura</li>
    <li> Pontos Sprint</li>
</ul>
<br><br>

## - Ficha RPG

Cria uma ficha com as características do personagem: Nome, Classe, Raça e Atributos (ex: Força, Destreza, Sabedoria, Inteligência...). 

Campos do formulário: 

<ul>
<li>	Nome (tipo texto)</li>
<li>	Classe (tipo select)</li>
<li>	Raça (tipo radio)</li>
<li>	Atributos - no mínimo 2 (ex: Força, Destreza, Sabedoria, Inteligência...) com botões para incrementar e decrementar para cada</li>
</ul>

No total, 10 pontos podem ser distribuídos entre os atributos.

Quando o usuário pressiona o botão “enviar”, escreve na tela as informações do personagem criado. 
<br><br>

## - Formulário Formatura

Formulário com informações pessoais para festa dfe formatura:

<ul>
<li>	Nome – campo do tipo input texto</li>
<li>	Curso – campo do tipo select com pelo menos 3 opções (informática, analise de sistema, ciência da computação, engenharia de computação...)</li>
<li>	Gênero – campo do tipo radio com pelo menos 3 opções (masculino, feminino, outro)</li>
<li>	Quantidade de convidados – campo com botão de incremento e decremento que deve ser limitado a 0 ou 5</li>
</ul>

Cada vez que o usuário clicar no botão “Adicionar”, as informações do aluno são salvas no localStorage e o formulário é limpo

Ao clicar no botão “Exibir lista” escreve na tela todos os alunos cadastrados. 

Ao clicar no botão “Limpar lista” exclui todos os valores já adicionados.
<br><br>

## - Pontos Sprint

Um squad composto por 3 desenvolvedores consegue entregar 15 pontos distribuídos em diversas atividades. 

Não há um número fixo de pontos para cada desenvolvedor, porém as atividades sempre são distribuídas de forma que todas sejam finalizadas.

A tela mostra o total de pontos disponíveis (15 pontos) e um campo para exibir a quantidade de pontos que cada um dos 3 desenvolvedores é responsável. 

Para cada desenvolvedor há um botão para incremento (+) e outro para decremento (-). 

Ao clicar nesses botões o valor do desenvolvedor é alterado e o valor total também.

O valor total deve sempre ser limitado a 0 ou 15. E o valor dos desenvolvedores devem ser distribuídos seguindo a disponibilidade do valor total. 

Ao inserir ou remover um ponto para determinado desenvolvedor, a pontuação geral também é alterada, seguindo o padrão.

Quando o usuário pressiona o botão "enviar" mostra na tela a pontuação de cada desenvolvedor. 

<br><br>
# 🚀 Tecnologias
<div>
  <img loading="lazy" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">  
  <img loading="lazy" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">  
  <img loading="lazy" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
</div>
