# Introdução a criação de websites com HTML5 e CSS3

## 1 - Introdução ao HTML
- Tim Nerners-Lee;
- 1991: HTML 1;
- 2014: HTML 4.

**Elemento HTML**
- **Tag de abertura:** define qual o tipo de elemento, o que ele vai fazer na tela;
- **Atributo** (dentro da tag de abertura), não obrigatório: pode mudar alguma funcionalidade, aparência ou dizer alguma coisa ao navegador;
- **Conteúdo**;
- **Tag de fechamento** (nem todos os elementos tem tag de fechamento).

**Estrutura básica**
- **!DOCTYPE html**: diz para o navegador que estamos escrevendo um dcumento html5;
- Elemento **html**: contém todo o conteúdo do documento;
- Elemento **head**: contém meta informações;
- Elemento **title**: dentro de "head"; título do site que aparece na aba do navegador;
- Elemento **body**: no mesmo nível de "head"; conteúdo da página, visível ao usuário.

## 2 - Entendendo o que é semântica
- Em 2014, com o html5, surgiram novos elementos que têm mais significado, tornando as marcações mais fáceis de serem compreendidas;

Alguns exemplos de elementos semânticos são:
- **section** : seção genérica de conteúdo;
- **header** : cabeçalhos (da página ou de parte da página);
- **article** : conteúdo relevante dentro da página;
- **aside** : conteúdo relacionado ao conteúdo principal da página;
- **footer** : rodapé (da página ou de pare da página).

## 3 - Como usar textos e links
- É possível inserir diversas formas de conteúdo em uma página web, mas ainda assim o texto continua sendo importante e relevante;
- Elemento **h1** : Título da página;
- Elemento **h2** : Título da seção;
- Elemento **h3** : Título de artigo;
- Elemento **p** : Parágrafo (utilizado por exemplo para o conteúdo de um artigo).
- Elemento **a** : conhecido como âncora; serve para interliga vários conteúdos na web

Atributos do elemento **a**:
- **href=""** : hyperlink para onde a âncora está apontando; pode apontar também para emails, iniciando com "mailto:"
- **target=""** : indica como esse link vai ser aberto; por exemplo "_blank" que diz para abrir a página em uma nova aba do navegador.

## 4 - Como inserir imagens em seu site

- O elemento **img** é o responsável por inserir imagens;
- Este elemento não possui tag de fechamento;

Atributos do elemento **img**:
- **src=""** : é obrigatório e guarda o caminho da imagem, que pode estar dentro dos documentos da página ou de outro lugar da web;
- **alt=""** : não é obrigatório mas é altamente recomendado para melhorar a acessibilidade. Ele mostra a descrição da imagem quando ela não é carregada e leitores de tela usam essa descrição para falar para os usuários o que aquela imagens significa.

## 5 - Como organizar listas com HTML
- As listas servem para agrupar uma coleção de itens;
- Elemento **ul** : unordered list ou lista não ordenada. Neste caso a ordem dos itens não é importante;
- Elemento **ol** : ordered list ou lista ordenada. Neste caso a ordem dos itens é importante;
- Elemento **li** : é um item da lista (tanto ul, como ol).

## 6 - Introdução e conceitos básicos do CSS3
Introdução:
- Linguagem de estilo;
- Cria regras de estilo para elementos ou grupo de elementos;
- Estrutura:
    - **Seletor:** "nome" do elemento html que iremos estilizar;
    - **Declarações:** entre chaves, são declaradas as propriedades e seu valor.
- Para criar regras diferentes para elementos com mesmo nome, utilizamos ID e CLASS:
    - **ID**: no html são declarados dentro do elemento como id="nome_do_id" e no css, o nome do id precedido por um **hash**
    - **CLASS**: no html são declaradas dentro do elemento como class="nome_da_classe" e no css, o nome da class precedido por um **ponto**.

Conceitos básicos:
- O navegador representa cada elemento html como uma caixa retangular, chamada **box model**;
- Com o CSS é possível alterar a aparência dessa caixa;
- O Box Model tem quatro áreas:
    - **margin** : espaçamento entre elementos;
    - **border** : circunda o padding;
    - **padding** : espaçamento entre a borda e o conteúdo;
    - **content** : retângulo interno que representa o elemento (texto, imagem, etc).

## 7 - Estilizando elementos, textos e listas
Algumas propriedades para estilizar elementos:

**PADDING e MARGIN** : três formas de atribuir valores
1. Colocando **dois** valores, para as partes (nesta ordem) superior e inferior;
2. Colocando **quatro** valores, para as partes (nesta ordem) superior, direita, inferior e esquerda;
3. Usando as propriedades específicas para cada lado: 
    - **padding-top**
    - **padding-right**
    - **padding-bottom**
    - **padding-left**

**BACKGROUND** : atalho para várias outras propriedades como:
- **background-color** : altera a cor de fundo;
- **background-image** : insere uma imagem de fundo;
- **background-position** : altera o posicionamento de um background inserido.

Algumas formas diferentes de alterar a cor de fundo são:
1. **background-color: <nome_da_cor>**;
2. **background-color: <codigo_hexadecimal_da_cor>**;
3. **background: <nome_da_cor>**.

**BORDER** : pode receber três valores (largura, cor e estilo - nesta ordem).
- Largura: pixels, centímetros, milímetros...
- Cor: nome da cor, código hexadecimal da cor...
- Estilo: sólida, pontilhada, tracejada...

Podemos usar propriedades específicas para cada lado da borda:
- **border-top**
- **border-right**
- **border-bottom**
- **border-left**

Caso as características da borda sejam as mesmas para todos os lados, podemos utilizar a propriedade de duas maneiras diferentes:
1. Utilizando apenas a propriedade **border** com os três valores, por exemplo:
    - **border: 3px solid #505050;**
2. Utilizando as três propriedades específicas:
    - **border-width: 3px;**
    - **border-style: solid;**
    - **border-color: #505050;**

Podemos criar regras mais específicas ainda definindo os lados e os aspects da borda, como por exemplo em:
- **border-top-width: 3px;**
- **border-top-style: solid;**
- **border-top-color: #505050;**

**BORDER-RADIUS** : permite arredondar os cantos de um elemento (unidades mais comuns são Pixels e Porcentagem). Exemplos:
- **border-radius: 10px** : aplica arredondamento de 10px nos quatro cantos do elemento;
- **border-radius: 50%** : aplica arredondamento de 50% nos quatro cantos do elemento (curiosidade: neste caso, um quadrado é transformado em um círculo);
- **border-radius: 10% 20% 15% 22%** : aplica diferentes arredondamentos em cada canto do elemento, seguindo a mesma ordem que vimos em padding e margin: top, right, bottom, left;

## 8 - Estilizando textos

- **font-family** : altera a fonte do texto.
    - Podemos atribuir mais de um valor à propriedade **font-family** para que, caso a primeira não esteja disponível no dispositivo, a próxima entre como backup, por exemplo:
        - **font-family: Verdana, Arial;**

- **font-size** : altera o tamanho do texto (não é a única disponível, mas a unidade que usaremos é o Pixel);

- **font-style** : altera a aparência do texto (normal, itálico...);

- **font-weight** : altera o "peso" do texto.
    - Pode receber valores numéricos ou palavras chave indicando o peso, como **bold**.