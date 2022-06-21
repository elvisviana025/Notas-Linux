# Notas "Linux" 💻

## Descrição 📝
Repositório criado para armazenar anotações sobre o sistema operacional **Linux** e alguns de seus comandos de terminal.

## Sumário 📑
1. [Como utilizar o Linux dentro do Windows](#id01)
2. [Comandos do Terminal](#id02)
* 2.1. [Comandos Básicos](#id02.1)

<br>

<a name="id01"></a>
## 1. Como utilizar o Linux dentro do Windows
Para utilizar o sistema operacional Linux dentro de um computador que utiliza o sistema operacional Windows faremos uso da **virtualização**: 

> Virtualização é o ato de criar uma versão virtual (ao invés de real) de algo, incluindo a simulação de uma plataforma de hardware, sistema operacional, dispositivo de armazenamento ou recursos de rede.

Um dos softwares mais utilizados para a virtualização é o **Virtualbox** da oracle, que ocupa aproximadamente 300 MB de memória. Para a instalação da Virtualbox e de sistemas operacionais, como o Linux, veja essa playlist do canal **Hardware e Redes Brasil**:

🔗 [Playlist "Curso de Virtualização"](https://www.youtube.com/playlist?list=PLAp37wMSBouCqJnY-Qck_XDwplEud3ELc)

Veja nesse artigo da Alura mais informações sobre virtualização:

🔗 [Artigo "VirtualBox e Máquinas Virtuais"](https://www.alura.com.br/artigos/virtualbox-maquinas-virtuais?utm_source=gnarus&utm_medium=timeline)

Depois de instalado, caso opte pelo Linux Ubuntu e ele não abra em **tela cheia**, recomendo este vídeo com um tutorial para abrir o sistema operacional em tela cheia e deixá-lo mais rápido:

🔗 [Vídeo "Instalar Adicionais para Convidado Virtualbox Ubuntu 22.04 | Deixar Ubuntu em Tela Cheia VirtualBox"](https://www.youtube.com/watch?v=CLlHSIupiSc&ab_channel=DITOCARVALHO)

<br>

<a name="id02"></a>
## 2. Comandos do Terminal
A seguir, comandos utilizados para manipular pastas, arquivos, e outras funcionalidades no terminal do Linux.

<a name="id02.1"></a>
### 2.1. Comandos Básicos

Manipular o terminal:
```
$ clear [limpa o terminal]
$ pwd [informa o diretório do terminal]
$ cd Desktop [mudar diretório]
$ echo "Bem vindo ao curso de Linux da Alura" [impirmir no terminal]
$ man comando [exibe informações de manual de um comando específicado]

```
Listar diretórios:
```
$ ls [listar diretórios]
$ ls -l [listar diretórios e permissões]
$ chmod +x realizabackup [adiciona permissão de execução]
```
Manipular arquivos:
```
$ touch arquivo.txt [criar arquivo]
$ echo "Faithless" > musicas-favoritas.txt [criar ou sobrescrever arquivo]
$ echo "REM" >> musicas-favoritas.txt [adicionar texto ao arquivo]
$ cat musicas-favoritas.txt [abrir arquivo no terminal]
$ tac musicas-favoritas.txt [abrir arquivo no terminal ao contrário]
$ head musicas-favoritas.txt [exibe primeiras linhas de arquivo]
$ tail musicas-favoritas.txt [exibe últimas linhas de arquivo]
$ mv mensagem.txt bemvindo2.txt [renomear arquivo]
$ cp bemvindo2.txt bemvindoCópia.txt [copiar arquivo]
$ rm arquivo3.txt [excluir arquivo]
$ find ~ -name teste.txt [procura local de um arquivo]
$ nano teste.txt [abre editor de texto]
```
Manipular diretórios:
```
$ mkdir workspace [criar diretório]
$ rmdir workspace [excluir diretório]
$ rm -r workspace [excluir diretório que tenha conteúdo]
```
Compactar arquivos e diretórios:
```
$ zip -r work.zip workspace/ [compactar em Zip, com subdiretórios]
$ unzip work.zip [descompactar]
```
Listar processos do computador:
```
$ ps [lista os processos que estão rodando]
$ ps -ef [lista com mais detalhes]
$ top [lista processos e consumo de CPU]
$ ps -ef | grep firefox [para filtrar algum processo pelo nome]

```






