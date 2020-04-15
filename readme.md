# VIM

## Porque gosto de usar VIM

Nunca vou poder dizer que sei tudo.

Muitas pessoas falam que com VIM é possível ser muito rápido.
Mas não é uma questão de o quão rápido você pode ser usando o VIM.
Eu gosto de usar o VIM porque eu não preciso pensar.

-- Michael Hill diz: O gargalo não está na digitação.
Você pode digitar mais rápido no VIM mas não é importante porque a digitação não
é o que atrasa o trabalho.

Então, não há razão para usar o VIM já que digitar mais rápido não aumenta a produtividade.

### O que atrasa meu trabalho

Digitar rápido não nos faz produzir mais.

O que diminui nossa produtividade é o tempo em que gastamos **pensando**.
Pensar não gasta somente tempo, gasta a cabeça.
A medida em que o dia vai passando, nossa cabeça vai cansando.
Por isso é importante a gente economizar nosso cérebro pensando em coisas que
são importante para o projeto em que estamos atuando.
Não queremos gastar tempo e pensamento com o nosso editor.

É por isso que usar o VIM ajuda.

### Como o VIM ajuda a eu pensar menos

O VIM me fornece uma linguagem para expressar as mudanças que eu quero fazer
no código de uma maneira eficiente e muito fácil.

**Não falamos a linguagem do VIM, o VIM fala a nossa língua.**
Isso quer dizer que não precisamos pensar ou gastar tempo com o editor.
Assim como não pensamos para falar com alguém,
não precisamos gastar a cabeça para usar o VIM.

É simplesmente colocar as mãos no teclado,
detectar a alteração no código que queremos fazer e pronto.
É mágico e também muito prático.

> A característica mais importante do VIM
é a habilidade de entender a linguagem humana (usando Inglês)

Quando usamos a maioria dos editores de textos,
cada tecla que digitamos resulta em um caractere no documento.
Para esses editores, a **inserção** de texto é a ação mais importante.

O VIM tem em mente que a maior parte do tempo a gente está **editando** texto,
e ele é otimizado para isso.

## Sintaxe da linguagem

### Verbo + Substantivo (Objeto)

**d** => delete

**w** => word

**dw** => delete word

### Comandos podem ser repetidos ou desfeitos

**.** repete a operação

**u** desfaz a operação

Podemos definir uma alteração e depois executá-la em
diversas partes do texto.

### Verbos no VIM

A operação que você quer fazer no texto.

* **d** => Delete
* **c** => Change (deleta e entra no modo de inserção)
* **>** => Indent
* **v** => Visually select
* **y** => Yank (copy)
* **p** => Paste
* **r** => Replace
* **s** => Substitute (Replace and goes to insert mode)
* **x** => Cuts single character

### Movimentos

* **$** => Final da linha
* **G** => Go to end (final do arquivo)
* **0** => start of line (inicio da linha)

### Substantivos (como objetos do verbo) e Movimentos

* **w** => word (uma *palavra* para frente)
* **b** => back (uma *palavra* para trás)
* **2w** => duas palavras
* **2j** => duas linhas abaixo

Todos os movimentos podem ser usados como objeto de um verbo.

### Advérbios

* **iw** => "inside word" (dentro da palavra)
* **it** => "inside tag" (dentro da tag)
* **i"** => "inside quotes" (dentro das aspas duplas)
* **ip** => "inside paragraph" (dentro do parágrafo)
* **as** => "around sentence" (em volta da frase)
* **a"'** => "around quotes" (em volta das aspas duplas)

### Objetos parametrizados

* **f** => "find" (encontre o próximo caractere)
* **F** => "find backwards"(encontre o caractere anterior)
* **t** => "till (until) (até o próximo caractere)
* **T** => "till backwards (until) (até o caractere anterior).
* **/** => search (encontre a próxima busca)
* **?** => search backwards (encontre antes do cursor)
