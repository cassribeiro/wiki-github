<h1 align = center> 🐧 Comandos em GNU/Linux 🐧 </h1>

<p align = center>
  Bem-vindo a este guia prático e simples com <strong>30 comandos fundamentais do GNU/Linux</strong>, <br> com explicações e exemplos para ajudar no aprendizado e facilitar o uso no dia a dia.
</p>

## ▸ ls
Um dos comandos mais utilizados o `ls` é utilizado para listar arquivos ou diretórios. <br>
**Exemplo de Aplicação:** <br>
Para listar o conteúdo do diretório root basta digitar o comando `ls /`.

## ▸ rm
Responsável por apagar arquivos, diretórios e sub-diretórios. <br>
**Exemplos de Aplicação:** <br>
O comando `rm teste.txt` apaga o arquivo chamado "teste.txt" no diretório atual.

## ▸ cp 
Este comando copia arquivos para outros arquivos ou para diretórios podendo copiar um ou múltiplos arquivos. <br>
**Exemplo de aplicação:** <br>
Copiando o arquivoA para o arquivoB no mesmo diretório `$ cp arquivoA arquivoB`

## ▸ mv 
Posibilita que arquivos e diretórios sejam movidos e renomeados, o arquivo de origem é apagado quando copiado. <br>
**Exemplo de aplicação:** <br>
Para mudar o nome do arquivo "teste.txt" para "testel.txt" é utilizado o comando `mv teste.txt testel.txt`.

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
Proporciona que o computador seja desligado ou reiniciado, todos os usuários são avisados que o computaor será delisgado. Esse comando pode ser utilizado pelo usuário root ou a opção `-a` pelo usuário já cadastrado no sistema. <br>
**Exemplo de Aplicação:** <br>
O comando `shutdown -h now` desliga o computador imediatamente.

## ▸ find 
Usado para procurar arquivos e diretórios diretamente no sistema de arquivos.<br>
**Exemplo de Aplicação:** <br>
Procura por todos os arquivos com extensão `.txt` a partir do diretório corrente(.). `$ find . -name “*.txt”`

## ▸ less
Permite que o usuário faça a paginação de um arquivo ou a entrada padrão. Esse comando pode ser usando como leitura de arquivo que oculpam mais de uma tela ou a tela toda. <br>
**Exemplo de Aplicação:** <br>
O comando `less /etc/passwd` permite que o arquivo "/ect/passwd" seja exibida de forma paginada.

## ▸ tail
Palavra vinda do inglês e significa **"cauda"**, é um comando que exibe as últimas linhas de um arquivo. <br>
Usando o `-n` especifica o número de linhas finais que o `tail` vai mostrar de um arquivo e o `-f` mostra as últimas linhas finais de um arquivo enquanto outro processo grava mais linhas. <br>
**Exemplo de Aplicação:** <br>
Para exibir as 40 últimas linhas do arquivo messages `$ tail –n 50 /var/log/messages`

## ▸ wc 
Conta o número de linhas, palavras e letras dentro de um arquivo ou entrada padrão. <br>
**Exemplo de Aplicação:** <br>
Para mostrar a quantidade de linhas, palavras e letras é usado o comando `wc / etc/passwd` do arquivo "/etc/passwd".

## ▸ grep
Usado em tarefas administrativas o commando `grep` é usado como filtro para linhas de um determinado arquivo, onde procura por uma expressão regular como padrão.<br>
**Exemplo de Aplicação:** <br>
Procurando todas as linhas começadas com a letra **u** no arquivo `/etc/passwd`. O acento circunflexo simboliza o início de uma linha:<br>
`$ grep "^u" /etc/passwd`

## ▸ whatis 
O `whatis` tem como função exibir o que determinado programa faz. <br>
**Exemplo de Aplicação:** <br>
Digitando `whatis ls` será mostrado a descrição do comando `ls`. 

## ▸ passwd
Este comando funciona como um gerenciador de senhas podendo ser utilizado para alterar as senhas dos usuários.<br>
**Exemplo de Aplicação:** <br>
Para mudar a senha do usuário uira:<br>
`# passwd uira` <br>
`Enter new password for ‘uira’:`

## ▸ sort 
Organiza as linhas de um arquivo de texto ou entrada padrão, essa organização é feita por linhas divididas em campos. <br>
**Exemplo de Aplicação:** <br>
O comando `sort texto.txt` organiza o arquivo "texto.txt" em ordem crescente. 

## ▸ chattr 
Essencial para proteger arquivos, é um comando que pode modificar atributos de arquivos e diretórios indo além das permissões padrão (rwx).<br>
**Exemplo de Aplicação:** <br>
 Adicionando todos os atributos:`chattr +AacdiSsu teste.txt` 

## ▸ cut
Mostra seções de cada linha do arquivo. <br>
**Exemplo de Aplicação:** <br>
O comando `cut -b 1,3 /etc/passwd` pega a primeira e a terceira letra de cada linha do arquivo "/etc/passwd".

## ▸ diff 
É usado para comparar dois arquivos linha a linha. <br>
**Exemplo de Aplicação:** <br>
Comparando o arquivo texto.txt com texto1.txt e exibindo suas diferenças na tela: `diff texto.txt texto1.txt`

## ▸ patch
Atualiza os arquivos texto através das diferenças geradas pelo comando `diff`. <br>
**Exemplo de Aplicação:** <br>
Esse comando `patch -pO<texto.diff` aplica as diferenças no arquivo "texto.diff" nos arquivos originais. 

## ▸ last 
Exibe todas as informações de entrada(login) e saída(logout) de usuários do sistema.<br>
**Exemplo de Aplicação:** <br>
Para mostrar a listagem geral e o nome da máquina: `last -a -`

## ▸ finger
Mostra detalhes sobre os usuários de um sistemas. <br>
**Exemplo de Aplicação:** <br>
O comando `finger` mostra os dados de todos os usuários conectados no sistema. 

## ▸ echo
Eficiente na construção de scripts o comando **echo** mostra mensagens o que facilita o usuário a acompanhar sua execução.<br>
**Exemplo de Aplicação:** <br>
`echo[mensagem]`e para que não ocorra um salto de linha após a exibição da mensagem é usado o `echo -n`.

## ▸ chmod
Muda a permissão de acessso a um arquivo ou diretório, o usuário pode escolher se um outro usuário ou grupo possa ter permissão para ler, gravar e executar um arquivo. <br>
**Exemplo de Aplicação:** <br>
Esse comando `chmod a=rw teste.txt` permite que todos os usuários exatamente (=) para leitura e gravação do arquivo "teste.txt".

## ▸ df
O comando `df`(disk free) exibe a capacidade utilizada de um sistema de arquivos em termos de espaço e inodes (estrutura que descreve um objeto do sistema de arquivos). <br>
**Exemplo de Aplicação:** <br>
Exibindo a capacidade do disco montado como raiz: `df -h /`

## ▸ du
Mostra o espaço ocupado por um arquivo e sub-diretório do diretório atual. <br>
**Exemplo de Aplicação:** <br>
O comando `du -h` mostra o espaço ocupado em formato Kb e Mb ao invés de blocos. 

## ▸ free
Mostra a quantidade de memória RAM livre e utilizada do sistema. <br>
**Exemplo de Aplicação:** <br>
Exibindo a memória em KB: `free`

## ▸ isattr
Lista os atributos de um arquivo ou um diretório do diretório atual <br>
**Exemplo de Aplicação:** <br>
Esse comando `lsattr -R` faz uma lista com atributos de um diretórios e subdiretórios.

## ▸ chown
Permite alterar o nome do dono e/ou grupo de arquivos. <br>
**Exemplo de Aplicação:** <br>
Muda o dono do arquivo teste.txt para pinguin: `chown pinguin teste.txt`

## ▸ tee
Envia o resultado do programa para a saída padrão e para um arquivo ao mesmo tempo. <br>
**Exemplo de Aplicação:** <br>
O comando `tee listagem.txt` mostra a saída do comando que será mostrada normalmente na tela e ao mesmo tempo gravar o arquivo "listagem.txt".
