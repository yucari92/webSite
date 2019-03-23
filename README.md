# webSite
O Git é uma ferramenta de controle de versão baseada no sistema de arquivos, ou seja, podemos fazer a associação de uma pasta diretamente a um repositório.
Então, vamos criar um novo diretoŕio que contera os arquivos do nosso 
projeto.

Mas, como essa é uma pasta qualquer em nosso computador, será que o git sabe 
que esta pasta conterá os arquivos do nosso projeto?Como podemos indicar que 
essa pasta será nosso futuro repośitório.

Quando realizamos mudança em um arquivo que esta sendo rastreado pelo git mas não foi commitado , a mensagem que aparecerá é changes to be commited, conforme 
abaixo:

# On branch master
#
# Initial commit
#
# Changes to be committed:
#   (use "git rm --cached <file>..." to unstage)
#
#  new file:   index.html
#
Perceba também que podemos usar o comando git rm --cache e nome do arquivo 
para tirar o arquivo da área de transferencia
------------------------------------------------

Ao modificarmos um arquivo que já foi commitado uma vez e consultarmos novamente
o status do nosso repositório teremos a mensagem changes not staged to commit.
conforme a seguir:

# On branch master
# Changes not staged for commit:
#   (use "git add <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#    modified:   index.html
#
no changes added to commit (use "git add" and/or "git commit -a")


