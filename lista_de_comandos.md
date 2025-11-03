# **Lista de comandos**

## Como iniciar um repositório no Git
`git init`

## Verificar e modificar configurações do git
`git config --global user.name "MeuNome"`
`git config --global user.email "seu@email`

## Rotina básica do Git
`save` # Salve o arquivo.

`git add <arquivo>` # Adiciona o arquivo na stating area do Git.

`git commit -m "mensagem relevante"` # Adiciona ao repositório local como um ponto na linha do tempo indicando as alterações feitas.

`git status` # Ele te diz exatamente o estado atual de tudo e em quais áreas conceituais os meus arquivos estão.

## Rotina *não tão* básica assim...
1. Situação: Atualizei meus arquivos no repositório local e fiz o backup no GitHub
- Salvei este passo (`git add "arquivo.md` > `git commit -m "mensagem"` > `git push`

2. Situação: Atualizei os arquivos no GitHub e quero sincronizar com o repositório local ou o meu colaborador atualizou depois de mim e quero sincronizar com meu repositório local
- Salvei este passo (`git add "arquivo.md` > `git commit -m "mensagem"` > `git pull`)

3. Situação do "mundo ideal": já inicio com o `git pull`
- `git pull` > edito os arquivos como preferir > `git status` > `git add "arquivo.md` > `git commit -m "mensagem"` > `git push`
