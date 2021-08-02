<h1>Conceitos de Branch (ramificação)</h1>

* git checkout -b "novo-botao"
<br><em>Primeiro crie a Branch e depois faça as edições. 
<br>Checkout sai da branch <b>Main</b> e vai para a <b>novo-botao</b>
<br>Crie o arquivo <b>botao.md</b> no CodeStudio e seu conteúdo.</em>

* git add .
* git commit -m "adicionando arquivo botao.md ao branch novo-botao"
<br><em>Adicionando ou Atualizando o arquivo <b>botao.md</b> ao Branch <b>novo-botao</b></em>

* git push origin novo-botao
<br><em>Envia para o projeto no GitHub na branch (ramificação) que estamos trabalhando agora: <b>novo-botao</b>.</em>

<h1>Juntar ramificações</h1>

* git checkout main
<br><em>Use git checkout main para ir para a branch (ramificação) main, que é a ramificação que deverá ser usada e irá receber a ramificação novo-botao.</em>

* git merge novo-botao
<br><em> Merge (juntar) a ramificação novo-botao ao em uso, main.</em>

* git push origin main
<br><em>Envia para o projeto no GitHub na branch (ramificação) main, e o arquivo botao.md irá aparecer na ramificação main.</em>




