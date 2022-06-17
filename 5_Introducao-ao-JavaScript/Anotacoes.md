# Introdução ao JavaScript

## 1 - História, evolução e aplicações

### 1.1 - Características gerais da linguagem
- Interpretada: roda em tempo real (não faz compilação do código);
- Baseada em Protótipos: 
- Multiparadigma;
- Comumente utilizada em aplicações web client side;
- Segue o padrão ECMAScript.

### 1.2 - Evolução
- 1997: ECAMScript 1 - First edition;
- 1998: ECAMScript 2 - Editorial changes only
- 1999: ECMAScript 3 - Regular Expressions; try/catch;
- 2000: ECMAScript 4 - Never released;
- 2006: ECAMScript 5 - "strict mode"; JSON support; String.trim(); Array.isArray(); Array Iteration Methods;
- 2015: ECMAScript 6 - muitas atualizações.

### 1.3 - Aplicações
- Web;
- Mobile;
- Smartwhatches;
- Games;
- Internet of Things;
- APIs.

## 2 - Recursos básicos da linguagem

### 2.1 - Comentários
- Para comentários de uma linha, utilizar duas barras à esquerda **//**
- Para comentários de várias linhas, utilizar barra e asterísco à esquerda para iniciar **/*** e asterísco e barra à direita para encerrar ***/**
- Atalho no VS Code: ctrl + /

### 2.2 - Variáveis e constantes
- **Variável:** espaço reservado na memória para armazenamento de um valor que pode ser alterado após a atribuição inicial;
- **Constante:** idem à Variável com a diferença de que o valor não pode variar após a atribuição inicial. 

### 2.3 - Funções
- São blocos de código que realizam uma tarefa específica;
- Para declarar usa-se a palavra reservada "function", em seguida o nome da função, os parâmetros de entrada entre parênteses, o bloco de código referente ao que a função deve retornar (utilizando a palavra reservada "return") entre chaves. Por exemplo:

function soma (a, b) {
    return a + b;
}
- Para invocar a função, usa-se o nome da função, seguida dos valores dos parâmetros entre parênteses. Por exemplo:

soma (5, 3);

