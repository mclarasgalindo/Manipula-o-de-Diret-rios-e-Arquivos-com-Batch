# Comandos Bat

## O que são?
Os comandos BAT (ou batch) são uma sequência de instruções que podem ser executadas no Prompt de Comando (CMD) do Windows. Esses comandos são usados para automatizar tarefas do sistema operacional, como copiar arquivos, mover arquivos, executar programas e muito mais. Um arquivo BAT é basicamente um script com uma extensão .bat, que contém uma série de comandos do sistema operacional que são executados em ordem.

## Comandos comuns em arquivos bat

### ECHO: Escreve na tela
#### Exemoplo:
. echo " Hello" >hello.txt

### CLS: Limpa os comandos.
#### Exemplo:
C:\>cls< enter>

### MOVE: Move (recorta) um arquivo de um diretório para outro.
#### Exemplo:
. MOVE C:\Arquivos\documento.txt C:\Backup\

### rmdir: comando é ótimo para remover diretórios não usados e vazios de forma segura.
#### Exemplo:
. rmdir C:\PastaVazia

### dir : mostra os arquivos da pasta abaixo, com isso entendo que seria do nível abaixo e não do nível acima. Talvez seja uma questão de nomenclatura.
#### Exmploe: 
. dir C:\Usuários\SeuNome\Documentos

### cd:  serve para navegar entre diretórios e visualizar o diretório atual.
#### Exemplo:
. cd C:\Arquivos

### mkdir:  é usado para criar novos diretórios ou subdiretórios no sistema.
#### Exemplo
. mkdir NovoDiretorio: Cria um diretório chamado "NovoDiretorio" no diretório atual.

### type: é um comando interno que exibe o conteúdo de um arquivo de texto.
#### EXemplo
. type nome_do_arquivo.txt

### rename: serve para mudar o nome de arquivos ou diretórios, desde que o novo nome não exista.
#### Exemplo
. rename arquivo.txt novo_arquivo.txt: Renomeia o arquivo "arquivo.txt" para "novo_arquivo.txt".
. ren C:\Pasta\AntigoDiretorio NovoDiretorio: Renomeia o diretório "AntigoDiretorio" para "NovoDiretorio".

### TAB: serve para completar.
#### Exemplo:
. dir D:<pressione TAB>
