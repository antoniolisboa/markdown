# Tutorial de Markdown
Markdown é uma linguagem de marcação que pode ser utilizada para varias coisas, por exemplo em anotações pessoais ou simplesmenta na criação de uma página estática de html utilizando [Pandoc](https://pandoc.org/installing.html "Página para download do pandoc"). O que realmenter torna o Markdown útil é a sua fácil construção sua e sintaxe simples. 

## Criando arquivo
Para criar seu primeiro markdown é simples basta escrever um arquivo com a extenção *.md* ou com a extenção *.markdown* e pronto basta a começar a edição.

## Visualizando meu arquivo markdown
Para os usuários de vscode recomendo que utilizam a exteção *Markdown Preview Enhanced* ela permite visualizar seu texto em markdown em tempo real enquando você está trabalhando nele como mostra a imagem.

![extencao vscode](images/vscode_extencao.png)
## Paragráfo
Para se obter um paragrafo em markdown basta pular uma linha.

~~~
1 Primeiro paragráfo.
2 continuando o primeiro paragráfo.
3 
4 Segundo paragráfo.
5 continuando o segundo paragráfo.
~~~

Primeiro paragráfo.
continuando o primeiro paragráfo.

Segundo paragráfo.
continuando o segundo paragráfo.

## Títulos
Os títulos são definidos pelo *#* seguido do *Título*.

~~~
 # Título equivalente ao h1 em html
 ## Título equivalente ao h2 em html
 ### Título equivalente ao h3 em html
 #### Título equivalente ao h4 em html
 ##### Título equivalente ao h5 em html
 ###### Título equivalente ao h6 em html
~~~

# Título equivalente ao h1 em html
 ## Título equivalente ao h2 em html
 ### Título equivalente ao h3 em html
 #### Título equivalente ao h4 em html
 ##### Título equivalente ao h5 em html
 ###### Título equivalente ao h6 em html

 ## Texto em itálico
Para se escrever um texto em itálico basta utilizar _*_ _*_ ou *_* *_* colocando o texto na parte interna.

~~~
1 *texto em itálico 1*
2 _texto em itálico 2_
~~~

*texto em itálico 1*
_texto em itálico 2_

 ## Texto em negrito
 A escrita de um texto em negrito é semelhante ao em itálico com algumas pequenas mudanças. Para deixar em negrito use _**_ _**_ ou *__* *__* adicionando o texto na parte interna.

 ~~~
1 **texto em negrito 1**
2 __texto em negrito 2__
~~~

**texto em negrito 1**
__texto em negrito 2__

 ## Links
 A dicionar links em markdown é muito simples.
 1. Link direto
 ~~~
 1 https://github.com/antoniolisboa
 2 <https://github.com/antoniolisboa>
 ~~~
https://github.com/antoniolisboa
<https://github.com/antoniolisboa>

 2. Link em trecho de texto
 ~~~
 [Antonio Github](https://github.com/antoniolisboa)
 ~~~
 [Antonio Github](https://github.com/antoniolisboa)

 3. Link em trecho de texto com title
 ~~~
 [Antonio Github](https://github.com/antoniolisboa "Minha página no github")
 ~~~
 [Antonio Github](https://github.com/antoniolisboa "Minha página no github")

 ## Citações
 Citação é reliazada utilizando o *>* ela pode ser de uma linha ou mutltiplas linhas.

 ~~~
 >Citação de uma linha
 ~~~
 >Citação de uma linha

  ~~~
 >Citação de multiplas linhas
 >Linha 1
 >Linha 2
 >Linha 3
 ~~~
 >Citação de multiplas linhas
 >Linha 1
 >Linha 2
 >Linha 3

 ## Lista não ordenada
 Lista de itens não ordenados pode ser feita utilizando _*_ ou *-*.
 ~~~
 * Paises
    * Brasil
    * Portugal
 * Continentes
    * Europa
    * Oceania
 ~~~

 * Paises
    * Brasil
    * Portugal
 * Continentes
    * Europa
    * Oceania

~~~
 - Paises
    - Brasil
    - Portugal
 - Continentes
    - Europa
    - Oceania
 ~~~

 - Paises
    - Brasil
    - Portugal
 - Continentes
    - Europa
    - Oceania
