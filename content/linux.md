# Linux 

## Introdução

## Conhecendo o Terminal

Para acessá-lo basta buscá-lo na Taskbar ou utilizar o comando `Ctrl + Alt + T`, há uma série de comandos para se lembrar:

| Atalho | Função | 
| --- | --- | 
| `man [comando]` | Explica o funcionamento de um comando selecionado para o usuário |
| `pwd` | Mostra ao usuário onde em que diretório ele está localizado | 
| `ls ou dir` | Lista os diretórios na pasta onde o usuário está |
| `ls -l` | Lista os diretórios na pasta onde o usuário está com detalhes |
| `cd` | Utilizado pelo usuário para mudar o diretório onde se localiza |
| `cd ..` | Volta para o diretório anterior |
| `cd /` | Volta para o diretório raiz |
| `cd ~` | Volta para a pasta pessoal |
| `history` | Exibe um histórico de todos os comandos utilizados durante a execução do terminal |
| `mkdir [nome do diretorio]` | Cria um diretório |
| `Ctrl + C` | Cancela o comando atual em funcionamento |
| `Ctrl + Z` | Pausa o comando atual |
| `Ctrl + W` | Apaga uma palavra na linha atual |
| `Ctrl + U` | Apaga a linha inteira |
| `Ctrl + R` | Busca um comando recente |
| `Ctrl + L ou clear` | Limpa o terminal |
| `!!` | Repete o último comnado | 
| `exit` | Sai do terminal |
| `mv [nome da pasta] [novo nome da pasta]` | Renomeia uma pasta |
| `mv dir/~` | move um diretório para o diretório pessoal |
| `touch [nome-do-arquivo]` | Cria um arquivo vazio |
| `cp [nome do arquivo] [endereço]` | Copia um arquivo para um endereço específico |
| `rm - r ou rmdir + [nome do diretório]` | Remove um diretório |
| `rm [nome do arquivo]` | Remove um arquivo |

## Exercícios Práticos de Revisão:
1. Abra o Terminal no Linux
2. Crie uma pasta de nome "Ubuntu" dentro da pasta Documentos
3. Mova a pasta Ubuntu para o diretório pessoal
4. Crie um arquivo vazio de nome teste.txt dentro da pasta Ubuntu
5. Renomeie o arquivo como linux.txt
6. Crie uma cópia deste arquivo na pasta Downloads
7. Exiba todos os comandos digitados no terminal
8. Execute a ajuda do comando ls
9. Execute o manual do comando mv
10. Pare a execução do manual
11. Saia do terminal utilizando sequência de teclas
12. Exclua a pasta Ubuntu
13. Exclua o arquivo linux.txt
14. Limpe o terminal
15. Utilize o comando para sair do terminal

## Lidando com arquivos .txt

Primeiramente, criamos um arquivo.txt e em seguida o comando `nano.txt` para abri-lo em um editor de textos.

| Atalhos | Função | 
| --- | --- | 
| `Ctrl + J` | Justifica o texto | 
| `Alt + U ` | Desfaz a última ação | 
| `Alt + E` | Refaz a última ação |
| `Alt + A` | Marca o Texto |
| `Alt + 6` | Copia o Texto | 
| `Ctrl + U` | Cola o texto |
| `Ctrl + T` | Verifica a ortografia(apenas em inglês) |
| `Ctrl + /` | Substitui termos no arquivo | 
| `Ctrl + O` | Salvar o texto | 
| `Ctrl + X` | Fecha o nano |
| `Cat + [nome do arquivo]` | Vizualizar o arquivo fora do nano |
| `Tac + [nome do arquivo]` | Vizualiza o arquivo com as linhas invertidas |
| `Head + [nome do arquivo]` | Mostra as 10 primeiras linhas de um arquivo |
| `Tail + [nome do arquivo]` | Mostra as 10 últimas linhas de um arquivo |
| `>` | Direciona um comando para outra entrada |
| `<` | TDireciona a entrada de um arquivo para a saída de um comando |
| `>>` | Adiciona um novo comando a um arquivo |
| `cal` | Mostra o calendário do mês atual | 
| `date` | Mostra a data |
| `grep [nome do arquivo]` | Busca um texto específico dentro de algum arquivo |
| `[comando] | [comando] ` | Possibilita usar dois comandos juntos |
