# Comandos git

1. git config

Quando você está utilizando o Git pela primeira vez ou com uma instalação nova, em um projeto colaborativo, esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada commit.

2. git init

Esse é o comando que você irá utilizar para criar um novo projeto de git. O comando irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvaguardar alterações etc.

3. git clone

Esse comando Git cria uma cópia exata de um repositório já existente.

**Então… quando usar git init e quando usar git clone? O git clone é mais avançado, uma vez que ele mesmo executa um comando git init internamente. Além disso, ele verifica todo o conteúdo do projeto.**

4. git add

Esse comando Git adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados. Oferece diferentes possibilidades de sintaxe.

## $ git add seu_arquivo (esse comando irá adicionar o arquivo em específico ao repositório)

## $ git add * (esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório)

5. git commit

É fundamental se estabelecer uma diferença entre git add e git commit:

    git add adiciona seus arquivos modificados à fila para serem submetidos a um commit posteriormente. Os arquivos não passaram por um commit.
    O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. Por outro lado, se você não adicionar nenhum arquivo, o git não fará o commit de nada.

É possível combinar as duas ações em um único comando: $ git commit -a.

Também é possível adicionar uma mensagem para a execução de um commit. Exemplo:

## $ git commit -m “seu comentário”

6. git branch

É comum na maior parte do tempo possuir múltiplas variações em seu repositório Git, chamadas de branches (“ramificações”). A grosso modo, um branch é um caminho independente de desenvolvimento, uma alternativa.

A princípio pode parecer fácil se perder em diversos caminhos, mas o comando git branch facilita o gerenciamento de tudo isso. Com diferentes parâmetros, é possível listar, criar ou apagar os branches.

7. git checkout

Ainda sobre branches, esse comando Git pode ser utilizado para trocar de uma ramificação para outra.

8. git remote

O comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.

9. git push

Esse comando serve para subir suas modificações para um repositório remoto conectado anteriormente com git remote.

10. git fetch

Quando você precisa baixar as mudanças criadas por outros membros do seu projeto colaborativo, você precisa do comando Git fetch. A partir desse comando, você irá receber todas as informações de commits, para avaliar, antes de aplicar essas alterações na sua versão local do repositório.

11. git pull

O comando Git pull baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu contreúdo para a última versão.

12. git stash

Esse comando Git armazena temporariamente seus arquivos modificados em uma área chamada stash (“esconderijo”), sem interagir com os outros arquivos até ser necessário.

13. git help

Existem inúmeros comandos no Git, muito mais do que os 25 dessa lista, cada um com sua função, parâmetros e características. Felizmente, o próprio Git tem o comando help para trazer ajuda diretamente no terminal.

14. git merge

Esse comando Git integra as mudanças de dois branches diferentes em um único branch. Ele precisa ser iniciado a partir de um branch já selecionado, que será mesclado com outro, com o nome passado por parâmetro.

15. git show

Quer detalhes específicos sobre um commit que o log não mostra? O comando Git show é a resposta.
