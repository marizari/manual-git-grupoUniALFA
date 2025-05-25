## **O QUE SÃO BRANCHES (RAMIFICAÇÕES)🌱 ?**

- *Branch* significa "ramo" ou "ramificação".
- São linhas do tempo alternativas no projeto, permitindo que você desenvolva novas funcionalidades sem afetar a linha principal;
- A *branch main* (ou master, antigamente) é a linha do tempo principal do projeto.

- `Resumo:` *Branches* são "linhas do tempo" diferentes do projeto. A principal geralmente se chama `main`. Você pode criar novas branches para testar ou desenvolver algo sem afetar a principal

*EXEMPLO PRÁTCIDO DA CRIAÇÃO DE UMA BRANCH (RAMIFICAÇÃO 🌱)*

`git branch nova-branch`
Isso tem que estar dentro de um repositório.


---

## **🔧 CRIAR, MUDAR E DELETAR BRANCHES**
    Branches (ou ramificações) permitem que você trabalhe em diferentes versões do seu projeto sem afetar diretamente o código principal (geralmente o branch main). Isso é útil para desenvolver novas funcionalidades, corrigir bugs ou testar algo novo.

### Criar uma nova branch:
    Para criar um novo branch e já mudar para a mesma, use o comando:

`git checkout -b nome-do-branch`


**Ou, em duas etapas:**
`git branch nome-do-branch` # Cria o branch
`git checkout nome-do-branch` # Troca para a branch selecionada no comando


*Exemplo:*
`git checkout -b feature/pagina-contato`
Isso cria um branch chamado feature/pagina-contato e te coloca nele.

### 🔄 MUDAR DE BRANCH
    Para trocar para outro branch existente, use:

`git checkout nome-do-branch`

*Exemplo:*
`git checkout main`
Você volta para o branch principal.


### 🗑️ DELETAR UM BRANCH:
    Depois de finalizar e mesclar seu branch, é uma boa prática deletá-lo para manter o repositório limpo.

**Para deletar localmente:**
`git branch -d nome-do-branch`

*Exemplo:*
`git branch -d feature/pagina-contato`
 Use -D (maiúsculo) se quiser forçar a exclusão, mesmo que o branch não tenha sido mesclado.

**Para deletar do repositório remoto:**
`git push origin --delete nome-do-branch`

*Exemplo:*
`git push origin --delete feature/pagina-contato`

**Dica Usual**
    Use o comando abaixo para ver os branches existentes e qual está ativo:
``git branch`









