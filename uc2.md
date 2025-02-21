# Aula 2

- Os elementos (Marcações) são conhecidos como tags.
- As tags podem possuir somente abertura ou abertura/encerramento.

1. Principais tags.
<h1></h1> até <h6></h6> ---> Títulos.
<p> </p> ---> Parágrafos.
<a> </a> ---> Link.
<img>  ---> Tag responsavél por apresentar uma imagem.
<strong> </strong> ---> Tag semântica. Indica uma força na palavra/frase
<em> </em> ---> Tag semântica. Indica uma ênfase na palavra/frase
<b> </b> ---> Coloca uma frase/palavra em negrito.
<i> </i> ---> Coloca uma frase/palavra em itálico
<br> ---> Realiza uma quebra de linha.
<hr> ---> Cria uma linha horizontal.
<div> </div> ---> Cria um bloco contendo outras tags.

2. Realizando a comunicação do CSS com o HTML
- CSS interno ---> Fica no arquivo html e é separado pela tag <style> </style>.
- CSS externo ---> É um arquivo separado do arquivo HTML. Possui a extensão .css e é a forma mais recomendada.
- CSS Inline ---> É utilizado na tag no HTML. Deve ser usado com cautela.

3. Estilizações básicas no CSS
- ``color`` : cor ---> Trocar a cor da letra
- ``background`` : fundo ---> Mudar o fundo
- ``font-size`` : tamanho da fonte  ---> Mudar o tamanho da fonte




# Aula 3

## SELETORES NO CSS
=> É a forma como você irá chamar um determinado elemento do `html` no `CSS`
1. tag ---> Basicamente, você chama a tag em si para realizar a estilização.
* Quando você chama diretamente a tag, cuidado para não estilizar todos os elementos que possui aquela tag.

2. #id ---> Você cria um identificador único na tag do elemento [html] e chama esse identificador no css.

3. .class ---> Você cria um ``[apelido]`` na tag do elemento e esse ``[apelido]`` pode ser utilizado quantas vezes necessárias inclusive em outras tags diferentes.

## SISTEMA DE CORES 
1. ``nome da cor ``---> Especifica o valor da cor através do nome da cor
2. ``Hexadecimal`` ---> Especifica o nome da cor através de uma sequência alfa-numérica
3. ``rgb`` ---> Especifica a cor através da intesidade do ref[vermelho], greedn[verde] , blue [azul].
4. ``rgba`` ---> São os mesmos valores do rgb, porém, com o valor do alpha[opacidade]


# Aula 4
## HTML

1. <img> ---> Tag responsável por inserir uma imagem interna ou externa.
- src ---> Fonte da imagem que voce quer exibir
- alt ---> é o texto alternativo caso a fonte da imagem está quebrada e por questões de acessibilidade.
ex: <img src="caminho_da_imagem" alt="descrição da imagem">

2. Listas
<ul></ul> ---> Informa que existirá itens e a posição desses itens não importa. Lista não ordenada. 
<ol></ol> ---> Informa que existirá itens e a posição desses itens IMPORTA. Lista ordenada.
<li></li> ---> É cada item da lista, independente da lista

3. Tag de link
`<a></a>` ---> é utilizada para gerar um texto clicavel. Link 
- href ---> é uma propriedade onde você irá informal qual o caminho que o link irá enviar o usuário.
ex: <a href="caminho_do_link">Lugar clicavel</a>


## CSS

1. ``font-family: Arial, Helvetica, sans-serif;`` ---> Propriedade que altera a tipografica,(Tipo de fonte) utilizado no elemento.

2. ``padding`` ---> é o espaçamento interno de um conteúdo até a borda.
3. ``margin`` ---> é o espaçamento externo do elemento em relação a outro elemento.
4. ``border`` ---> é a borda do elemento.
