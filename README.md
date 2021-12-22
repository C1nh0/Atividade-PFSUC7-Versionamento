# Atividade-PFSUC7-Versionamento

#Instalar o Git no Opensuse Leap 15.3

sudo zypper in git-core

#Configurar o Git

git config --global user.name "usuario"

git config --global user.email "usuario@outlook.com"

#Criar a estrutura inicail do repositório git no computador local;

git init

#Verificar o status das alterações realizadas no repositório;

git status

#Adicionar arquivos ao histórico do projeto, na staging;

git add .

#Salvar a alteração no repositório;

git commit

#Visualizar as alterações feitas;

git log

#Visualizar informações sobre qualquer commit;

git show "número do commit"

#Informar a pasta remota;

git remote add origin "destino"

#Visualizar o repositório remoto;

git remove -v

#Publicar as alterações no repositório remoto;

git push -u origin master / branch

#Baixar as alterações do repositório remoto

git pull

#Ignorar arquivos

criar arquivo .gitignore / adicionar os arquivos a serem ignorados

#Clonar repositório

git pull: para baixar as atualizações do repositório remoto;

git clone: para clonar a pasta do repositório remoto;

#Criar uma Branch

git checkout -b "nome da branch" (-b cria a branch)

#Unificar as Branchs

git pull origin "nome da branch"

git merge "nome da branch"

#Resolver conflitos

editar manualmente os arquivos

#Criar tags

git tag -a "versão" -m "comentário"

#Visualizar tags criadas

git tag

#Publicar as tags

git push origin --tags

