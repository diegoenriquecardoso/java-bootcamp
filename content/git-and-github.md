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





