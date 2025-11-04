# **Lista de comandos**

## Como iniciar um repositório no Git
`git init`

## Verificar e modificar configurações do git
`git config --global user.name "MeuNome"` # Alterar o nome.

`git config --global user.email "seu@email` # Alterar o e-mail.

## Rotina básica do Git
`save` # Salve o arquivo.

`git add <arquivo>` # Adiciona o arquivo na stating area do Git.

`git commit -m "mensagem relevante"` # Adiciona ao repositório local como um ponto na linha do tempo indicando as alterações feitas.


## Outros comandos importantes
`git status` # Ele te diz exatamente o estado atual de tudo e em quais áreas conceituais os meus arquivos estão.

`git log` # Conferir as últimas versões que foram para o repositório local.

`git log -n 3 --abbrev-commit` # Script para conferência das versões, mas com mais detalhes (i. adicionado o número de versões que quero ver: "-n x") (ii. abreviar o código ID de cada versão: "--abbrev-commit)

`git diff <commit ID1 (velho)> <commit ID2 (novo)>` # Compara a diferenças entre duas versões definidas por você.

`git push` # Leva os arquivos de seu repositório local para o repositório remoto.

`git pull` # Leva os arquivos de seu repositório remoto para o repositório local.

## Para o README do meu perfil no GitHub

- Após  ``git add``, seus próximos passos para enviar isso ao GitHub serão:

- ``git commit -m "Cria README do perfil"`` (Para salvar localmente)

- ``git branch -M main` (Para garantir que sua branch principal se chama "main")

- ``git remote add origin git@github.com:meriofilho/meriofilho.git`` (Para conectar sua pasta local ao repositório no GitHub)

- ``git push -u origin main`` (Para enviar o arquivo)
