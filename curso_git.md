# **Curso Git/GitHub**
## **Dicionário**
### **Git**
O Git é um software de controle de versão — um programa que registra as mudanças feitas em arquivos (geralmente código) ao longo do tempo.

### **Git Hub**
O GitHub é uma plataforma que serve para armazenar seus repositórios na nuvem, colaborar com outras pessoas, abrir issues, fazer pull requests, e mostrar seu portfólio.

#### ***NOTA**: o arquivo ".md" é a extensão utilizada em todo arquivo markdown.*

## **Boas práticas no Git**
### Salvando um ponto na linha do tempo
É importante sempre deixar claro nas mensagens de atualização dos arquivos esses quatro pontos ao adicionar esse novo ponto de atualização.
1. Por que houve essa mudança?
2. Como o problema foi resolvido?
3. Efeitos causados pela alteração
4. Limitações das atualizações feitas

#### Lembre-se sempre, no commit: **Mais detalhes > Menos informações**

## **Diferentes áreas no Git**
- **Área de Desenvolvimento (Working Directory / Working Tree)**

É onde você edita os arquivos do projeto no seu computador.

- **Área de Staging (ou Index)**

É uma área intermediária entre o desenvolvimento e o repositório local.

- **Repositório Local (Local Repository)**

É onde o Git salva o histórico de versões do seu projeto no seu computador.

### **Resumindo**
_Área de desenvolvimento → **git add** → Área de staging → **git commit** → Repositório local_

## Rotina básica do Git

### Quando os comandos `git status`, `git add` e `git commit` são utilizados? 

- ``git status``: Use a qualquer momento para ver o que aconteceu no seu projeto (quais arquivos foram modificados, o que está pronto para salvar, etc.). É o seu "mapa".

- ``git add`` <arquivo>: Use antes de um commit para selecionar quais mudanças específicas você quer salvar. (Coloca as mudanças na "área de preparação" ou "stage").

- ``git commit -m "mensagem"``: Use depois do git add para salvar permanentemente as mudanças que você preparou no histórico do projeto, com uma mensagem explicando o que foi feito.

### Como interpretar os resultados de `git status`?

1. **Changes to be committed (Geralmente Verde)**:
- O que é: Mudanças que você já preparou com git add.
- O que fazer: Elas serão salvas no seu próximo git commit.

2. **Changes not staged for commit (Geralmente Vermelho)**:
- O que é: Arquivos que o Git conhece, mas que você modificou (ou deletou) e ainda não usou git add.
- O que fazer: Decida se quer incluí-los (com git add) ou descartar as mudanças (com git restore).

3. **Untracked files (Geralmente Vermelho)**:
- O que é: Arquivos novos que o Git nunca viu antes.
- O que fazer: Use git add <arquivo> para começar a rastreá-los.

4. **nothing to commit, working tree clean**:
- O que é: O estado perfeito. Tudo está salvo e não há mudanças pendentes.