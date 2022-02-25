---------------------------------------------------------------------------------

# COMANDOS GIT HUB 

- Comando **git remote add origin** https://github.com/MariaFranciscaSoares/Livro-Receitas-.git
- Comando **git remote -v**
    - Comando 1 e 2 cria um repositório remoto.
 - Comando **git push origin master**
   - Comando 3 envia o repositório *Local* para o *Remoto*.


---------------------------------------------------------------------------------

## Demonstração de como usar os comandos no Git para resolver conflitos no GitHub

*Observação: Foi feita um alteração no GitHub, alterando o index. Foi adicionado 
a receita Pavê.*

### Comandos no Git 

 -  Comando **git status**
    - A partir do momento que altera no *GitHub* o *Git* irá identificar um arquivo "novo" mostrando a mensagem que  é necessário mover para *Staged* e criar um *Commit*.
 - Comando **git add**  
      - Comando para adicionar na *Staged* o "novo" arquivo.
 - Comado **git status**
      - Agora git mostra a mensagem que o arquivo que esta na *Staged  e Staging Area* pronto para ser *commitado.*
 - Comando **git commit -m  "Adiciona a receita Pave"**
      - Comando que adiciona o arquivo que esta no *Staged*
         no *Commit.*
 - Comando **git push origin master**
       - Comando para enviar o *Repositório Local* para o *Repósitorio Remote*, no caso GitHub .
       -  Porém, irá dá erro e o *Git* informará um "merge conflit". Pois, o codigo foi  modificado no *GitHub* como vimos na primeira observação acima. Dessa forma, o *Repositório Remoto* possui alguma modficação que o *Reposítório Local* não possui, no caso a inclusão da receita Pavê. 
 - Comando **git pull origin master**
      - Comando para integrar o que esta no *Repositório Remoto* com o *Reposítório Local*. Desta forma, será resolvido o "merge conflict" que é  a  diferença dos programas  *local e remote.* 

 - Comando **git push origin master**
       -  Comando para enviar o programa para o GitHub .















