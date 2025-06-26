
# Resumos Git e GitHub

Reposítorio para armazenar resumos sobre Git e GitHub do curso [Git e Github para iniciantes](https://www.udemy.com/course/git-e-github-para-iniciantes/).

## 📒 Documentação:
 - [Documentação Git](https://git-scm.com/doc)
 - [Documentação GitHub](https://docs.github.com/pt)

## 💻 Resumos das aulas:

```git push origin main``` Envia (publica) as alterações locais para o repositório remoto na branch main.

```git status``` Mostra o estado atual dos arquivos no repositório.

```git add``` Adiciona arquivos ao estágio (prepara para commit).

```git commit -m "seu comentario aqui"``` Salva as alterações no repositório local com uma mensagem.

```git log``` Exibe o histórico de commits.

```git log --decorate``` Mostra o log de commits com referências (branch/tags).

```git log --author="nome"``` Mostra commits feitos por um autor específico.

```git shortlog``` Mostra resumo de commits agrupados por autor.

```git shortlog -ns``` Lista autores e número de commits (ordenado).

```git log --graph``` Exibe o histórico de commits em formato gráfico (ramificações).

```git diff``` Mostra as diferenças entre arquivos alterados e o último commit.

```git diff --name-only``` Lista apenas os nomes dos arquivos alterados.

```git checkout [nome-arquivo]``` Desfaz alterações no arquivo, restaurando do último commit.

```git reset HEAD [nome-arquivo]``` Remove o arquivo do estágio (unstage).

```git reset --soft``` Move o ponteiro do HEAD, mas mantém arquivos e staging.

```git reset --mixed``` Move o HEAD e desfaz o staging, mas mantém arquivos.

```git reset --hard``` Move o HEAD e descarta todas as alterações (perigoso!).

```git checkout -b "nome-do-branch"``` Cria e troca para uma nova branch.

```git branch``` Lista todas as branches.

```git branch -D testing``` Deleta a branch "testing".

```git config --global alias.s status``` Cria um atalho ("s") para o comando "status".

```git push origin main --tags``` Envia a branch main e todas as tags para o repositório remoto.

```git tag -a 1.0.0 -m "Readme finalizado"``` Cria uma tag anotada chamada 1.0.0 com mensagem.

```gitignore``` Arquivo de configuração que define quais arquivos ou pastas devem ser ignorados pelo Git (não versionados).
