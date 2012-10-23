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


