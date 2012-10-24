Comando para gerar o par de chaves:
ssh-keygen -t rsa -C "adelsontads@gmail.com"

Na pasta .ssh cat no arquivo:
cat id_rsa.pub

Copia o conteudo do arquivo e cola no ssh keys do "github"

##########################################################

Para clonar um repositório
git clone URL_REPOSITORIO


Configurar o nome e o e-mail para serem utilizados no comit(senão irá utilizar o nome do usuário no pc)
git config --global user.name "USER-NAME"
git config --global user.email "EMAIL"


Depois que criar ou modificar um arquivo:
git add ARQUIVO


Para comitar o arquivo:
git commit -m "MENSAGEM"


Para adicionar e comitar tudo de uma vez utiliza o comando(CUIDADO: ele comita tudo mesmo!):
git commit -am "MENSAGEM"


Para remover um arquivo(OBS: remove também do sistema):
git rm ARQUIVO
git commit -m "MENSAGEM"


Para o diff ficar colorido:
git diff --color


Para ver o histórico:
git log


Para ver algo similar ao diff:
git show


Para retornar um arquivo a versão que está no repositório (tipo revert):
git checkout ARQUIVO


Para listar o branch:
git branch


Para criar um novo branch:
git branch NOME_DO_BRANCH


Para mudar de branch:
git checkout NOME_DO_BRANCH


Para fazer um diff entre dois branchs:
git diff NOME_BRANCH NOME_OUTRO_BRANCH


Para ver detalhe dos commits de determinado arquivo:
git blame NOME_ARQUIVO


Para fazer um merge entre dois branchs:
git merge NOME_BRANCJ NOME_OUTRO_BRANCH


Para criar uma tag:
git tag NOME_DA_TAG


Para ir para tag:
git checkout NOME_DA_TAG


Para mostrar informações sobre uma tag:
git show NOME_DA_TAG


Para retirar as mudanças que foram feitas(e colocar numa pilha, ex: antes de baixar as mudanças do servidor "oringinal"):
git stash


Para retirar as mudanças da pilha:
git stash pop


Para comitar as alterções para o servidor origin:
git push origin master

