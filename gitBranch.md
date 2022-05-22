![](https://content.codecademy.com/courses/learn-git/git-diagram-1.svg)

     git branch
 - - -
 
 Retorna uma lista com as branchs do repositório
 
 <br>
 
     git branch -a
 - - -
 
 Retorna uma lista com as branchs do repositório, incluindo as branchs remotas
 
 <br>
 
     git branch -d branch_name
 - - -
 
 Remove a branch do repositório local e do remoto (se existir)
 
 <br>
 
     git branch -D branch_name
 - - -
 
 Remove a branch do repositório permanentemente (se existir) e do remoto (se existir)
 
 <br>
 
     git branch -m old_name new_name
 - - -
 
 Renomeia uma branch do repositório
 
 <br>
 
     git branch -v
 - - -
 
 Mostra o estado da branch atual
 
 <br>
 
     git branch -vv
 - - -
 
 Mostra o estado da branch atual, incluindo o estado de cada commit
 
 <br>
 
     git branch -vvv
 - - -
 
 Mostra o estado da branch atual, incluindo o estado de cada commit, incluindo o estado de cada arquivo

<br>

    git branch new_branch
---
Comando utilizado para criar uma nova branch

<br>

        git checkout branch_name
---
Comando utilizado para mudar para uma branch

<br>

    git checkout -b new_branch
---
Comando utilizado para criar uma nova branch e mudar para ela

<br>

_______________________________________________________________________________________________________________
<br>
<br>
<br>

_______________________________________________________________________________________________________________

    git merge branch_name
---
Comando utilizado para mesclar duas branchs no repositório local 

<br>

    git merge --abort
---
Comando utilizado para cancelar a mesclagem

<br>

    git merge --continue
---
Comando utilizado para continuar a mesclagem

<br>

    git merge --no-commit
---
Comando utilizado para não mesclar e sim apenas mostrar o que seria mesclado

<br>

_______________________________________________________________________________________________________________
<br>
<br>
<br>

_______________________________________________________________________________________________________________

    git clone remote_location clone_name
---
## Comando utilizado para clonar um repositório remoto para o local 

<br>

    git remote -v
---
Comando utilizado para verificar os repositórios 

<br>

    git fetch
---
Comando utilizado para buscar os repositórios remotos   