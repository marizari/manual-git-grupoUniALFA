 1. git init
Inicia um repositório Git local.

bash
Copiar
Editar
$ mkdir meu-projeto
$ cd meu-projeto
$ git init
 Simulação: Cria a pasta .git e começa a controlar seu projeto com Git.

 2. git clone <URL>
Clona um repositório remoto para sua máquina.

bash
Copiar
Editar
$ git clone https://github.com/usuario/repositorio.git
 Simulação: Baixa todos os arquivos e o histórico de commits.

 3. git status
Mostra o estado atual dos arquivos no diretório.

bash
Copiar
Editar
$ git status
 Simulação: Mostra se há arquivos modificados, novos ou prontos para commit.

 4. git add <arquivo> ou git add .
Adiciona arquivos ao “staging” (área de preparação para commit).

bash
Copiar
Editar
$ git add index.html         # Um arquivo
$ git add .                  # Todos os arquivos modificados
 Simulação: Marca os arquivos que você quer incluir no próximo commit.

 5. git commit -m "mensagem"
Salva as mudanças no histórico do Git.

bash
Copiar
Editar
$ git commit -m "Adiciona página inicial"
 Simulação: Cria um ponto no tempo (snapshot) com todas as alterações adicionadas.

 6. git log
Mostra o histórico de commits.

bash
Copiar
Editar
$ git log
 Simulação: Lista os commits feitos, com hash, autor, data e mensagem.

7. git push
Envia os commits locais para o repositório remoto.

bash
Copiar
Editar
$ git push origin main
 Simulação: Atualiza o GitHub (ou outro remoto) com seus commits locais.

 8. git pull
Baixa as alterações do repositório remoto e mescla com o local.

bash
Copiar
Editar
$ git pull origin main
 Simulação: Atualiza seu projeto com as mudanças feitas por outras pessoas.

 9. git branch
Gerencia branches (ramificações).

bash
Copiar
Editar
$ git branch                 # Lista branches
$ git branch nova-feature   # Cria uma nova branch
$ git checkout nova-feature # Muda para a nova branch
 Simulação: Você pode trabalhar em novas funcionalidades sem afetar o código principal.

 10. git merge <branch>
Mescla outra branch na atual.

bash
Copiar
Editar
$ git checkout main
$ git merge nova-feature
 Simulação: Integra as mudanças feitas na nova-feature com a branch main.

 11. git remote -v
Mostra os repositórios remotos conectados.

bash
Copiar
Editar
$ git remote -v
Simulação: Exibe a URL do repositório remoto (como GitHub).

 12. git reset / git checkout --
Desfaz alterações locais.

bash
Copiar
Editar
$ git reset HEAD arquivo.txt            # Tira do staging
$ git checkout -- arquivo.txt           # Desfaz alteração local
Simulação: Reverte arquivos ao último commit.

 13. git diff
Mostra as diferenças entre os arquivos modificados e o último commit.

bash
Copiar
Editar
$ git diff
 Simulação: Mostra exatamente o que foi alterado nas linhas do código.

14. git stash
Salva alterações temporariamente para voltar depois.

bash
Copiar
Editar
$ git stash
$ git stash pop
 Simulação: "Guarda" suas alterações para que você possa mudar de branch ou resolver conflitos.

 15. git config
Configurações do usuário.

bash
Copiar
Editar
$ git config --global user.name "Seu Nome"
$ git config --global user.email "email@example.com"
Simulação: Define quem está fazendo os commits.

parte #