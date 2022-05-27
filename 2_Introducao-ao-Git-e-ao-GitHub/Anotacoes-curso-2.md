# Anotações do curso: Introdução ao Git e ao GitHub

## 1 - Introdução ao Git

- Trabalho com várias versões de um mesmo arquivo;
- Git: 2005, sistema de versionamento de código distrbuído;
- Linus Torvalds, também criador do Linux;
- Softwares são feitos de forma colaborativa;
- Git (repositório local) é diferente de GitHub (repositório remoto).

Benefícios do uso das duas tecnologias:
- Controle de versão;
- Armazenamento em nuvem;
- Trabalho em equipe;
- Melhorar seu código;
- Reconhecimento.

## 2 - Navegação via Command Line Interface e instalação

Comandos no terminal Linux:

- ls : lista todos os arquivos e diretórios contidos no diretório atual;
- cd : acesso a determinado diretório:
    - cd .. : sobe um nivel de diretório;
    - cd <nome_do_diretorio> : acessa o diretório determinado;
- clear : limpa a tela (também funciona com CTRL + l);
- mkdir <nome_do_diretrio> : cria um novo diretório no diretório atual;
- rm : remove um arquivo o diretório;
- cat : abre o arquivo indicado pelo usuário;
- pwd : exibe o endereço do diretório atual.

## 3 - Entendendo como o Git funciona por baixo dos panos

### 3.1 - SHA1:
- Secure Hash Algorithm;
- Conjunto de funções hash criptografadas;
- A encriptação gera um conjunto (único) de caracteres identificador de 40 dígitos.

### 3.2 - Objetos internos do Git:

Blob:
- Guarda o sha1 do arquivo.

Tree:
- Armazena o(s) Blob(s);
- Pode armazenar outro (s) Tree(s);
- Guarda o sha1 do diretório ("árvore").

Commit:
- Aponta para uma árvore;
- Aponta para um parent (último commit);
- Aponta para um autor;
- Aponta para uma mensagem;
- Guarda o sha1 do objeto.

## 4 - Primeiros comandos com Git e ciclo de vida dos arquivos

- git init : inicializa o git no diretório atual;
- git add * : prepara todas as alterações para serem "commitadas". Alterações mudam para o estado Staged;
- git commit -m "mensagem" : cria uma nova versão do repositório (localmente) considerando as últimas alterações.

## 5 - Introdução ao GitHub e outros comandos Git

- git config --list : mostra as configurações do Git na máquina;
- git remote -v : lista os repositórios remotos que tenho cadastrado;
- git remote add origin <endereço_repo_remoto> : aponta para o repositório remoto;
- git push origin main : empurra o commit do repositório local para o repositório remoto.