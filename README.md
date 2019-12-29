# Comandos do git

## GIT Config
Configurar nome de usuário: 
git config --global user.name "nome do usuario"
Configurar email:
git config --global user.email "email@usuario.com"

Listagem do que foi configurado
git config -l


## Fluxo de commit
Adicionar arquivo para staging area
git add "caminho/nomeArquivo.txt"
git commit -m "mensagem de commit"


## REMOTO

git remote show origin  
*Visualizar o endereço remoto*

git remote set-url origin \<url_do_seu_repositorio\>
*Como alterar a URL de um repo remoto*  


## branch

*cria o branch e já muda para ele*  
git checkout -b nome-do-branch  
