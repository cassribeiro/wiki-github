# Comando em Linux 🐧
## ▸ ls
Um dos comandos mais utilizados o `ls` é utilizado para listar arquivos ou diretórios. <br>
**Exemplo de Aplicação:** <br>
Para listar o conteúdo do diretório root basta digitar o comando `ls /`.

## ▸ rm
Responsável por apagar arquivos, diretórios e sub-diretórios. <br>
**Exemplos de Aplicação:** <br>
O comando `rm teste.txt` apaga o arquivo chamado "texto.txt" no diretório atual.

## ▸ cp 
Este comando copia arquivos para outros arquivos ou para diretórios podendo copiar um ou múltiplos arquivos. <br>
**Exemplo de aplicação:**<br>
Copiando o arquivoA para o arquivoB no mesmo diretório `$ cp arquivoA arquivoB`

## ▸ mv 
Posibilita que arquivos e diretórios sejam movidos e renomeados, o arquivo de origem é apagado quando copiado. <br>
**Exemplo de aplicação:**<br>
Para mudar o nome do arquivo "teste.txt" para "testel.txt" é utilizado o comando `mv teste.txt testel.txt`

## ▸ mkdir
O comando `mkdir` significa *"make directory"* que em português é *"criar diretório"*, ou seja é um comando que permite criar diretórios (pastas) dentro do atual ou em um especificado pelo usuário.<br>
**Exemplo de Aplicação:** <br>
Criar um novo diretório dentro da pasta atual deve se usuar o comando `mkdir nome da_pasta` <br>
Para criar um diretório em um caminho específico `mkdir /home/usuário/backup`

## ▸ cd 
Permite que o usuário entre em um diretório, necessitando de um permissão de execução para realizar essa ação. <br>
**Exemplo de Aplicação:** <br>
O comando `cd/` faz com que o usuário retorne ao diretório raíz. 

## ▸ touch 
Comando capaz de alterar a data e a hora de acesso e modificção de um arquivo. Podendo mudar a hora de acesso ou a hora de modificação, tem a possibilidade de ser os dois ao mesmo tempo.<br>
**Exemplo de Aplicação:** <br>
Modificando a data e hora de um arquivo, se o arquivo não existe será criado a partir daquele momento e se existir ocorre apenas a alteração. 
`$ touch -t AAAAMMDDhhmm.ss arquivo`

## ▸ shutdown

## ▸ find 
Usado para procurar arquivos e diretórios diretamente no sistema de arquivos.<br>
**Exemplo de Aplicação:** <br>
Procura por todos os arquivos com extensão `.txt` a partir do diretório corrente(.). `$ find . -name “*.txt”`

## ▸ less

## ▸ tail
Palavra vinda do inglês e significa **"cauda"**, é um comando que exibe as últimas linhas de um arquivo. <br>
Usando o `-n` especifica o número de linhas finais que o `tail` vai mostrar de um arquivo e o `-f` mostra as últimas linhas finais de um arquivo enquanto outro processo grava mais linhas. <br>
**Exemplo de Aplicação:** <br>
Para exibir as 40 últimas linhas do arquivo messages `$ tail –n 50 /var/log/messages`

## ▸ wc 
## ▸ grep
## ▸ whatis 
## ▸ passwd
## ▸ sort 
## ▸ chattr 
## ▸ cut
## ▸ diff 
## ▸ patch
## ▸ last 
## ▸ ping
## ▸ echo
## ▸ chmod
## ▸ df
## ▸ du
## ▸ free
## ▸ isattr
## ▸ chown
## ▸ tee
