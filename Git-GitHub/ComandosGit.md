

# Comandos introdutórios do Git



- Comando **ls** - *Listar pastas do diretório que você se encontra atualmente*.

- Comando **cd + nome da pasta** - *Entrar dentro da pasta*.

- Comando **cd ..** - **Para sair da pasta que você está **

- Comando **clear** *ou* **CRTL+L** - *Limpar tela*.

- Comando **mkdir + nome da pasta** - *Criar pasta*.

- Comando **git init**  - *Comando único, utilizado para que o Git inicie o gerenciamento no repositório*.

- Comando  **ls + -a** - *Lista pastas do diretório que você encontra-se mais pastas ocultas.* 

- Comando **echo** - *printa o que escreveu, exemplo:  "echo" + "mensagem" + ">" + "nome da pasta" irá jogar saída da função "echo" (no caso a mensagem) na pasta direcionada*

  

## Comandos para criação de um Commit 



**Introdução - Tracked ou Untracked** - O *Tracked*  é submetido em três pilares, sendo o primeiro *Unmodified* onde encontra-se os arquivos não modificados,  o segundo *Modified* que obtém os arquivos modificados e por terceiro *Staged* onde está os arquivos que estão preparados para fazer parte de outro agrupamento, no caso, o *Commit.*  O *Untracked* obtém os arquivos que ainda não foram rastreados pelo Git. 

**Remote Repository** - Repositório publicados em uma nuvem que podem ser públicos ou não. 

**Working Directory** - Obtém os arquivos que estão no diretório sendo editados. 

**Stagin Area** - Obtém os arquivos que estão em *Staged*.

**Local Repository** - Obtém todos os *Commit*.



- Comando **git add"*/ git add nomeDaPasta / git add .** - De modo geral, este comando envia todos os arquivos que estão no repositório local sendo da área *Tracked* ou *Untracked*  para *Staged*.
- Comando **git commit -m + "mensagem"** -  Este comando envelopa todos os arquivos que estão no *Staged* com significância através da mensagem escrita . Deste modo, quando o comando é aplicado, o Git obtém todos os arquivos do *Staged* e cria uma "foto" que ficará salva dentro do *Commit*, e os arquivos que está em *Staged* retornam para *Unmodified* reiniciando o ciclo. 
- Comando **git status** - mostra como está o diretorio da *Stagin Area*. Caso tenha algum arquivo em *Modified* o git irá exibir uma mensagem avisando que é necessário adicionar ao *Staged* e *Commitar* 









