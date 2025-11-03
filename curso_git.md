# **Dicionário**
## **Git**
O Git é um software de controle de versão — um programa que registra as mudanças feitas em arquivos (geralmente código) ao longo do tempo.

## **Git Hub**
O GitHub é uma plataforma que serve para armazenar seus repositórios na nuvem, colaborar com outras pessoas, abrir issues, fazer pull requests, e mostrar seu portfólio.

#### ***NOTA**: o arquivo ".md" é a extensão utilizada em todo arquivo markdown.*

# **Boas práticas no Git**
## Salvando um ponto na linha do tempo
É importante sempre deixar claro nas mensagens de atualização dos arquivos esses quatro pontos ao adicionar esse novo ponto de atualização.
1. Por que houve essa mudança?
2. Como o problema foi resolvido?
3. Efeitos causados pela alteração
4. Limitações das atualizações feitas

#### Lembre-se sempre, no commit: **Mais detalhes > Menos informações**

# **Diferentes áreas no Git**
- **Área de Desenvolvimento (Working Directory / Working Tree)**

É onde você edita os arquivos do projeto no seu computador.

- **Área de Staging (ou Index)**

É uma área intermediária entre o desenvolvimento e o repositório local.

- **Repositório Local (Local Repository)**

É onde o Git salva o histórico de versões do seu projeto no seu computador.

### **Resumindo**
_Área de desenvolvimento → **git add** → Área de staging → **git commit** → Repositório local_