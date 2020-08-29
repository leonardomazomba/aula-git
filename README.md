//Iniciar a linha do tempo
git init

//Adicionar o arquivo ou uma mudança de arquivo ao git
git add nome_arquivo

//Para adicionar todos os arquivos
git add .

//Gravar o arquivo nos repositorios do Github
git commit -m "alterado landingPage"

//Para verificar se há alterações ainda não gravadas ou arquivos não atualizados no git
git status

//Pegar os logs realizados no repositorio
git log

//Para mostrar uma alteração antiga
git show

//Criar uma ramificação de alterações sem afetar o projeto principal
git branch nome_feature

//Navegar para a feature
git checkout nome_feature

//Voltar para a principal
git checkout master

//Fazer o merge do repositorio principal com a feature
git checkout master
git merge nome_feature