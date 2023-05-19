### Link para download do Git no Windows
[https://gitforwindows.org/](https://gitforwindows.org/)


# História do Git

O Git foi criado em 2005 por Linus Torvalds para gerenciar o desenvolvimento do kernel do Linux. O objetivo era criar um sistema de controle de versão distribuído, que permitisse trabalhar em equipe e compartilhar código de forma eficiente. O Git se tornou popular rapidamente devido à sua rapidez, eficiência e facilidade de uso. Hoje em dia, é amplamente utilizado em projetos de software de todos os tamanhos e tipos.

## O que é Git

Git é uma ferramenta de controle de versão com foco em velocidade e integridade de dados. Tem a mesma função de outras ferramentas como SourceSafe, SVN e TFS. Você pode usar Git com o Github e também com o Bitbucket e Gitlab, pra citar alguns.
O Git permite que várias pessoas trabalhem no mesmo projeto simultaneamente, mantendo um histórico completo de todas as alterações feitas no código-fonte. Além disso, o Git permite que os desenvolvedores trabalhem offline, criem e gerenciem ramos (ou branches) do projeto e colaborem em diferentes versões do código-fonte. Ele é amplamente utilizado em projetos de software livre e comercial.

## GitHub

Github é um site que permite que você hospede seus repositórios(projetos) usando o Git lá. Outras pessoas podem ver seus projetos, baixa-los, olhar o seu código. E você também pode ver o código dos outros, participar de projetos e seguir outros desenvolvedores.
Sim, seguir tipo Facebook, só que você vai ver o código que as pessoas estão fazendo ao invés da opinião delas sobre política ou videos de gato e futebol.

## Git BASH
BASH usada para executar o Git a partir da linha de comando. 

## GUI do Git
Alternativa visual ao Git BASH

## Comandos Git 

[Lista de comandos do Git](https://comandosgit.github.io/)

### Help
O comando help pode ser usado isoladamente o em conjunto com um comando
  git help  / Git help add

### Repositório Local

* Criar novo repositório

~~~
git init
~~~

* Verificar estado dos arquivos/diretórios

~~~
git status
~~~

### Adicionar arquivo/diretório (staged area)

* Adicionar um arquivo em específico

~~~
git add meu_arquivo.txt
~~~

* Adicionar um diretório em específico

~~~
git add meu_diretorio
~~~

* Adicionar todos os arquivos/diretórios

~~~
git add .	
~~~

* Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)

~~~
git add -f arquivo_no_gitignore.txt
~~~

### Comitar arquivo/diretório

* Comitar um arquivo

~~~
git commit meu_arquivo.txt
~~~

* Comitar vários arquivos

~~~
git commit meu_arquivo.txt meu_outro_arquivo.txt
~~~

* Comitar informando mensagem

~~~
git commit meuarquivo.txt -m "minha mensagem de commit"
~~~

### Remover arquivo/diretório

* Remover arquivo

~~~
git rm meu_arquivo.txt
~~~

* Remover diretório

~~~
git rm -r diretorio
~~~


`git push`: Envia os commits locais para um repositório remoto.

`git pull`: Obtém e mescla as alterações do repositório remoto no branch local.

`git branch [nome do branch]`: Cria um novo branch no repositório.

`git checkout [nome do branch ou commit]`: Alterna para o branch especificado ou commit.

`git merge [nome do branch]`: Mescla o branch especificado com o branch atual.




