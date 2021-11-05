# Introdução

## O que é git e sua importância

Software muito importante para programadores pois permite controle de versão, armazenamento em nuvem, trabalho em equipe, melhoria do código e reconhecimento.

**GUI**(Ghrapic User Interface) x **CLI**(Command Line Interface)

# Comandos básicos no terminal

Comandos:

| Função | Windows | Linux |
| --- | --- | --- | 
| Possibilida navegação entre as pastas | cd | cd |
| Lista os diretórios na pasta em que o usuário se situa | dir | ls |
| Criar uma pasta | mkdir | mkdir |
| Deletar arquivos/Remover pasta com os arquivos de dentro | del/rmdir | rm-rf|
| Limpa o terminal | cls | clear(ou ctrl+L) |
| Auto-pesquisa | tab | --- |
| criar arquivo | echo \<nome do arquivo> >  \<nome do arquivo>.\<tipo do arquivo> | echo \<nome do arquivo> >  \<nome do arquivo>.\<tipo do arquivo> |

# Conceitos Fundamentais sobre o Funcionamento de Git

## SHA1

A sigla SHA significa Security Hash Algorithm, é um conjunto de funções hash criptográfias projetadas pela NSA (Agência de Segurança Nacional dos EUA).

## Objetos internos do Git

**Blob**: Objeto onde arquivos ficam guardados, contém metadados dentro, contendo o tipo do objeto, o tamanho, um \0 e o conteúdo de fato do arquivo.

**Tree**: Armazena Blobs, contém metadados, \0, sha1 e o nome do arquivo. Responsável por montar toda estrutura de onde estão localizados os arquivos.

**Commit**: Objeto de junção de todos os outros, aponta para Trees, Parents, Autor, timestamp e mensagem e também sha1. Dá significado para alterações em arquivos.

# Comandos e conceitos de Git

**Git Init**: Inicializa um repositório

**Tracked**/**Untracked**: Tracked se subdivide em três estágios diferentes que ciclam-se: **unmodified**(intocado), **modified**(com modificações feitas) e **staged**(onde ficam os arquivos preparados para fazer parte de outro agrupamento, para **fazer parte de um commit**).

**Git Add**: Move um arquivo untracked direto para staged.
![image](https://user-images.githubusercontent.com/93105584/140437584-5b542038-67d6-4df9-b1d0-30f4687f18f4.png)

**Git Restore**: Tira um ou mais arquivos do status de Staged.

**Git Status**: Diz se um arquivo está Untracked, Unmodified ou Staged

**Repositório**

![image](https://user-images.githubusercontent.com/93105584/140438099-e87d288f-8cfe-4371-ac01-663be17e84f7.png)

Como adicionar de um repositório local para um repositório remoto: Criar o repositório no github, copiar seu link, empurra de um para o outro, primeiramente se adicionando a origem através de:

> git remote add \<nome-do-arquivo>\<link-do-repositório

E então:

> git remote -v 

E por fim

> git push \<nome-do-arquivo> master

