Projeto inicial do git

Comandos:

git --version
* Exibe versão para confirmar se a instalação está correta.

git config --global user.email "you@example.com"
ou
git config --global user.name "Your Name"
* acessar github pelo email lá cadastrado.

Após abrir a pasta com o Git

git init
*iniciar git no repositorio main


git add nome_arquivo.ext
* colocar os arquivos em fila para serem comitados.

git status
* passar informação do status do git como mudanças para serem comitadas.

git commit -m "Primeiro Commit"
* lançar os arquivos.

git branch -M "main"
* mudar o nome da branch.

* Ir para o github https://github.com/willsbq/ e criar um novo projeto no repositório com o nome "ProjetoGit".

git remote add origin https://github.com/willsbq/ProjetoGit.git
* preparar para adicionar o arquivo com nome origin no projeto criado no GitHub.

git push -u origin main
* enviar origin para main



resumo

…or create a new repository on the command line
echo "# ProjetoGit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/willsbq/ProjetoGit.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/willsbq/ProjetoGit.git
git branch -M main
git push -u origin main

clear 
* limpar o Bash

VERSIONAMENTO DE FATO
criar outro arquivo no KodeStudio para informar os links de ajuda. "LinksVideos.md".

git add .
* adicionar todos os arquivos e ter um versionamento.
