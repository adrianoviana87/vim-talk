# Aprendendo a conversar com o Vim

## Não falamos a linguagem do Vim, o Vim fala a nossa língua

Isso quer dizer que não precisamos pensar ou gastar tempo com o editor.
Assim como não pensamos para falar com alguém,
não precisamos gastar a cabeça para usar o Vim.

É simplesmente colocar as mãos no teclado,
detectar a alteração no código que queremos fazer e pronto.
É mágico e também muito prático.

> A característica mais importante do Vim
é a habilidade de entender a linguagem humana (usando Inglês)

Quando usamos a maioria dos editores de textos,
cada tecla que digitamos resulta em um caractere no documento.
Para esses editores, a **inserção** de texto é a ação mais importante.

O Vim tem em mente que a maior parte do tempo a gente está **editando** texto,
e ele é otimizado para isso.

## Sintaxe da linguagem

### Quantidade + Verbo + Advérbio + (Substantivo (Objeto) / movimento)

Exemplo:

**2** => 2 -- quantidade

**d** => delete -- verbo

**a** => around -- advérbio

**w** => word -- movimento

**2w** => 2 words -- movimento

**h** => esquerda

**j** => abaixo

**k** => acima

**l** => direita

Ação:

**d2w** => delete 2 words

**daw** => delete around word

**2d2w** => 2 * delete around word

**d2j** => delete 2 lines down

### Comandos podem ser repetidos ou desfeitos

**.** repete a operação

**u** desfaz a operação

Podemos definir uma alteração e depois executá-la em
diversas partes do texto.

### Verbos no Vim

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
