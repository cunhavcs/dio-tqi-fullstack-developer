# Anotações Curso: Introdução a Programação e Pensamento Computacional

## 1 - Pensamento Computacional
- Processo organizado para resolução de problemas baseado no contexto da computação;
- Não se restringe apenas a problemas da área de computação, mas a problemas e questões de qualquer área;
- Baseado em quatro pilares:
    1. Decomposição;
    2. Reconhecimento de padrões;
    3. Abstração;
    4. Design de algoritmo.

### 1.1 - Decomposição
- Dado um problema complexo, devemos quebrá-lo em problemas menores, mais fáceis de resolver e mais gerenciáveis.

### 1.2 - Padrões
- Detecção de similaridades e diferenças.

### 1.3 - Abstração
- Processo intelectual de isolamento de um objeto da realidade;

### 1.4 - Algoritmos
- Sequência de passos com objetivo definido;
- Execução de tarefas específicas;
- Conjunto de operações que resultam em uma sucessão finita de ações;
- Conjunto de intruções: O que precisa ser feito + Qual a ordem de execução.

## 2 - Introdução à Computação

### 2.1 - Lógica de programação
- Tarefas do dia a dia sempre usam raciocínio lógico de alguma forma;
- Em programação tudo também deve estar baseado em raciocínio lógico;
- Fazer o programador pensar em forma racional;
- Permite que problemas sejam solucionados da melhor forma possível dentro do contexto;
- Decidir, por exemplo, entre performance ou segurança;
- Estudo da teoria de programação para saber o que diferentes linguagens de programação podem oferecer;
- Base para aprender alguma linguagem;
- Aprender a criar algoritmos (caminho para se chegar a uma solução).

Para desenvolver um programa:

1. Saber **O QUE** precisa ser feito (lógica);

2. Saber **COMO** isso será feio (depende da escolha de uma linguagem).

### 2.2 - Algoritmos

Tipos de representação:

1. Descrição narrativa;

2. Fluxograma ou diagrama de blocos;

3. Pseudocódigo ou linguagem estruturada. 

Descrição narrativa:

- Linguagem normal do dia a dia;
- Passos são descritos como devem acontecer;
- Exemplo: receita de bolo.

Fluxograma ou diagrama de blocos:

- Representação por formas geométricas;
- Cada forma tem significado distinto e expressam ações, instruções ou comandos a executar.

Pseudocódigo ou linguagem estruturada:

- Representação que mais se assemelha a uma linguagem de programação;
- Usa blocos, comandos de entrada e saída, variáveis, entre outros elementos que juntos foramarão um conjunto de alçoes a realizar;
- A língua nativa é utilizada para escrever o algoritmo (em nosso caso, o Português).

Fases para criar um algoritmo:

1. Definir o problema;
2. Verificar formas possíveis de solução;
3. Definir e escolher a melor forma de solução de acordo com o contexto;
4. Criar o algoritmo;
5. Analisar se o problema foi resolvido, caso contrário voltar à etapa inicial e repetir o processo.

### 2.3 - Tipos de dados, variáveis e constantes

Programa de computador:

- Instruções: ordens dadas ao cmputador, através do programa;
- Informações: dados que serão manipulados pelas instruções.

Tipos de dados:

1. Numérico inteiro;
2. Numérico real;
3. Literal ou string (entre aspas);
4. Lógico ou boleano (Verdadeiro: 1 ou Falso: 0).

Variável:

1. Posição (espaço) reservado na memória do computador;
2. Representada por um nome simbólico;
3. Seu valor pode variar durante a execução do programa;
4. Em algumas linguagens de programação, também é necessário informar o tipo e dado que ela irá armazenar;

Constante:

1. Idem aos itens 1 e 2 da Variável;
2. Seu valor **NÃO** pode variar durante a execução do programa;
3. Geralmente não e necessário informar o tipo de dado.

Regras para nomes de variáveis e constantes. **NÃO** pode conter:

1. Primeiro caractere numérico;
2. Espaços vazios (utilizar snake_case, camelCase ou PascalCase);
3. Caracteres especiais;
4. Palavras reservadas da linguagem;
- Observações:

    - Algumas linguagens são Casesensitive (diferencia letras maiúsculas e minúsculas);
    - Importante verificar as convenções e boas práticas de cada linguagem.

Variáveis compostas:

- Também chamadas de vetores ou arrays;
- Assemelham-se a uma planilha de Excel (armazenam diversos valores organizados em linhas e colunas);
- **Unidimensionais:** uma linha e várias colunas;
- **Bidimensionais:** várias linhas e várias colunas;
- Para atribuição de valores, é necessário informar a posição no vetor (a contagem sempre inicia no índice zero).

### 2.4 - Estruturas Condicionais

Estrutura condicional **Simples**:

- Se - If;
- É baseada em uma condição determinada;
- Caso a condição seja atendida, um bloco de comandos é executado.

Estrutura condicional **Composta**:

- Senão - Else;
- Diferente da condicional simples por executar outro bloco de comandos **senão** for atendida a condição determinada.

### 2.5 - Estruturas de Repetição
- Também é estabelecida condição para gerar um ponto de parada na repetição;
- Enquanto (while)...faça
- Para (for)...faça
- Repita...até

### 2.6 - Funções
- Similar ao conceito de função matemática (recebe um argumento e retorna um valor);
- Subprograma, subrotina;
- Blocos de instruções que realizam tarefas específicas;
- Vantagens:
    - Modularização do programa;
    - Código mais claro e conciso;
    - Reutilização de código.

### 2.7 - Linguagens de Programação
- Código fonte: será traduzido ou interpretado;
- Linguagem de alto nível: mais próxima à linguagem do humano;
- Linguagem de baixo nível: mais próxima à linguagem de máquina;
- Linguagem de máquina: códigos binários; forma "entendível" pelo computador;
- Tradução (compilação): geração separada da execução do programa objeto (execução mais rápida);
- Interpretação: programa fonte executado diretamente (maior flexibilidade).

### 2.8 - Paradigmas de Programação
- Tipo de estruturação ao qual a linguagem deverá respeitar;
- Escolha depende da tratativa definida para resolver o problema;
- Pode oferecer técnicas apropriadas para uma aplicação específica;

Principais paradigmas de programação:

- Imperativo (ou Procedural)
    - Instruções devem ser passadas na sequência em que devem ser executadas;
    - Espécie de passo a passo dos procedimentos;
    - Indicado para programas mais estáticos;
    - Vantagem de ser bem eficiente mas com código de difícil legibilidade.

- Funcional
    - Destaque para o uso de funções;
    - Problema dividido em blocos;
    - Indicado quando a solução é dependente de uma base matemática.

- Orientado à Objetos
    - Permite uma programação multiplataforma de uma mesma 
    maneira;
    - Origem na necessidade de produzir programas de forma mais rápida, com maior confiabilidade e a um menor custo;
    - Apoia-se nas características de classe e objeto;
    - Todos os objetos têm estados e cmportamentos.