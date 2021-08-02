<h1>Atividades no GitHub (online)</h1>

* Ir para o github https://github.com/willsbq/
<br><em>Criar um novo projeto no repositório com o nome "ProjetoGit".</em>

<h1>Projeto inicial do Git</h1>

<h2>Comandos</h2>

* git --version
<br><em>Exibe versão para confirmar se a instalação está correta.</em>

* git config --global user.email "you@example.com"
<em>ou</em>
git config --global user.name "Your Name"
<br><em>Acessar GitHub pelo email de cadastrado.</em>

<h2>Após abrir a pasta com o Git</h2>

* git init
<br><em>Iniciar git no repositorio <b>main</b> (ramificação principal).</em>

* git branch -M "main"
<br><em>Mudar o nome da Branch (ramificação, ramo).</em>

* git add nome_arquivo.ext
<br><em>Colocar os arquivos em fila para serem despachados(Commit).</em>

* git status
<br><em>Passar informação do estado do Git.</em>

* git commit -m "Primeiro Commit"
<br><em>Exportar os arquivos e acrescentar uma mensagem relacionada aos despachos.</em>

* git remote add origin https://github.com/willsbq/ProjetoGit.git
<br><em>Preparar para adicionar o arquivo com apelido "origin" no projeto criado no GitHub.</em>

* git push -u origin main
<br><em>Enviar origin para main</em>

* clear 
<br><em>Limpar o Bash.</em>

<h1>Resumo</h1>

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



<h1>VERSIONAMENTO DE FATO</h1>

* Criar arquivo "LinksVideos.md" no KodeStudio.
<br><em>Criar outro arquivo no KodeStudio para informar os links de ajuda.</em>

* git add .
<br><em>Colocar todos os arquivos em fila para ter um versionamento.</em>

* git commit -m "Info no readme e adição do arquivo com links de vídeos"
<br><em>Despachar os arquivos e passar informação relacionada com a exportação.</em>

* git push origin main
<br><em>Enviar para o GitHub no repositório com o apelido origin, que já foi adicionado com o endereço do projeto no GitHub, sem necessidade de informá-lo novamente.</em>
