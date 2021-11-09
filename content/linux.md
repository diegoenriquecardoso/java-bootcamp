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
| `[comando] \| [comando]` | Possibilita usar dois comandos juntos |
| `more` | Paginação de textos |
| `less` | Paginação de textos |
| `&` | Permite usar dois comandos separadamente, cada um com sua saída no terminal |
| `&&` | Permite usar dois comandos separadamente, com uma só saída |

## Comandos de Diretórios de Linux

| Descrição | Diretório |
| --- | --- |
| Binários principais dos usuários | /bin/ |
| Arquivos do sistema de Boot | /boot/ |
| Arquivos de dispositivos | /dev/ |
| Arquivos de configuração do sistema | /etc/ |
| Diretório dos usuários comuns do sistema | /home/ |
| Bibliotecas essenciais do sistema e os módulos do kernel | /lib/ |
| Diretório de montagem e dispositivos | /media/ |
| Diretório de montagem de dispositivos - mesmo que "media" | /mnt/ |
| Instalação de programas não oficiais da distribuição ou por conta do usuário | /opt |
| Armazena arquivos executáveis que representam comandos administrativos. Exemplo: shutdown | /sbin/ |
| Diretório para dados de serviços fornecidos pelo sistema | /srv/ |
| Diretório para arquivos temporários | /tmp/ |
| Segunda hierarquia do sistema, onde ficam os usuários comuns do sistema e programas | /usr/ |
| Diretório arquivos variáveis gerados pelos programas do sistema. Exemplo: logs, histórico da impressora, e-mail e cache | /var/ |
| Diretório do usuário root - O usuário root tem o total poder sobre o sistema. Podendo instalar, desinstalar, configurar | /root/ |
| Diretório virtural controlado pelo kernel | /proc/ |

| Comando | Função |
| --- | --- |
| Arquivo de informações do processador | `cat/proc/cpuinfo` |
| Exibir informações do processador | `lscpu` |
| Arquivo de informações da memória | `cat /proc/meminfo` |
| Exibir informações da memória física e virtual | `free` |
| Exibir informações detalhadas sobre o hardware | `lshw` |
| Exibir informações sobre hardware | `lshw -short` |
| Exibir o nome do kernel do sistema | `uname` |
| Exibir a versão do kernel | `uname -r` |
| Exibir a arquitetura do kernel | `uname -m` |
| Exibir a arquitetura do kernel | `arch` |
| Exibir todas as placas PCI conectadas | `lspci` |
| Exibir todos os dispositivos USB conectados | `lsusb` |
| Exibir o epsaço de cada arquivo e pasta no diretório pessoal consome no hd | `du -h ~` |
| Reiniciar o sistema | `reboot` |
| Reinicia o sistema | shutdown `-r` |
| Desliga o sistema rapidamente | `shutdown -h now` |
| Cancelar o shutdown sendo executado | `-c` |
| Desligar o sistema | `-h` |
| Suspender o funcionamento da máquina | `-H` |
| Desligar o sistema imediatamente | `sudo shutdown -h now` |
| Reiniciar o sistema imediatamente | `sudo shutdown -r now` |
| Informações sobre reinicialização do sistema | `last reboot` |
| Mostrar as tabelas de roteamento do kernel | `route -n` |
| Mostrar o tempo de processo de um comando | `time [comando]` |
| Tempo que o sistema está rodando | `uptime` |

## Rede, protocolos e Interfaces de Rede

### Redes 
> Rede de computadores é um conjunto de equipamentos interligados de maneira a trocarem informações e compartilharem recursos, como arquivos de dados gravados, impressoras, modems, softwares e outros equipamentos (Sousa, 1999)

**Rede Wan**
**Wide Area Network** ou **World Area Network** é uma rede geograficamente distribuída.

**Rede Man**
**Metropolitan Area Network** é uma rede metropolitana que interligam várias redes locais.

**Rede Lan**
**Local Area Network** é uma rede local de uma forma geral em um único prédio ou campus.

### Protocolos
> Protocolo é a "linguagem" usada pelos dispositivos de uma rede de modo que eles consigam se entender (Torres, 2004).

**IP - Protocolo de Internet - Endereço IP**: Números que identificam seu computador em uma rede.

**ICMP - (Internet Control Message Protocol)**: Tem por objetivo prover mensagens de controle na comunicação entre nós.

**DNS - Domain Name Server**: Esse protocolo de aplicação tem por função identificar endereços IP e manter uma tabela com os endereços dos caminhos de algumas redes.

### Interfaces de Rede
Interface de rede é um software e/ou hardware que faz a comunicação em uma rede de computadores. As interfaces de rede no Linux estão localizadas no diretório `/dev` e a maioria é criada dinamicamente pelos softwares quando são requisitadas. Exemplo: eth0 - Placa de rede Ethernet - cabeada A interface loopback é um tipo especial de interface que permite fazer conexões com você mesmo, com ela você pode testar vários programas de rede sem interferir em sua rede padrão, o endereço IP 127.0.0.1 foi escolhido para loopback.

## Fundamentos e Comandos de Rede

| Comando | Função |
| --- | --- |
| ifconfig | Exibe informaçõe sobre interface da rede e ip |
| hostname | Exibe informações sobre o Host |
| hostname -i | Exibe o número de endereço loopback do Host |
| hostname -I | Exibe o endereço de IP da rede | 
| dig host | Exibe informações sobre o DNS de um host |
| dig host +short | Exibe o número de IP de um host |
| w | Exibe informações detalhadas sobre o usuário do computador na rede |
| who | Exibe informações curtas sobre o usuáario do computador na rede |
| whoami | Exibe o nome do usuário do computador na rede |
| traceroute host | Exibe informações sobre a rota de sua rede até o host desejado |
| ping host | Testa um host |
| finger | Exibe informações sobre o usuário do computador na rede |

# Controle de Usuários








 

