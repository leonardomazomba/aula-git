# GIT E GITHUB

Guia prático para iniciantes.

### Instalação

https://git-scm.com/download

# SCENES

- [x] Você deseja criar pontos na história da produção do seu projeto
- [x] Você deseja verificar mudanças feitas no seu projeto

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.
- [x] Você adiciona as novas funcionalidades ao seu projeto em produção
- [x] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

- [x] Você quer colocar seu projeto na nuvem.

- [x] Você vai pegar um projeto já iniciado, para trabalhar com o time
- [x] Você precisa resolver um conflito.
- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

- [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.
- [x] Você precisa recuperar algo deletado.

* `git init` // inicia a linha do tempo
* `git add` // adiciona ou atualiza mudanças para irem para a linha do tempoo
* `git commit` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo / commit
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // gerenciar novas linhas do tempo
* `git checkout` // manipula as linhas do tempo
* `git merge` // unir linhas do tempo
* `git push` // envia alterações locais para o repositório remoto
* `git clone` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto


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