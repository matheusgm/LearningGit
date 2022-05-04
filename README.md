# LearningGit

git clone <url> : clonar um repositorio da url

git branch : visualizar as branches

git branch <nome> : criar um branch com o nome

git checkout <branch> : trocar de branch para a branch

git add . : adicionar todos os arquivos

git commit -m <msg> : commitar com a msg

git push origin <branch> : enviar arquivos da branch para o git

git pull origin <branch> : pegar os arquivos da branch


# Fazer commit e enviar para o git (na sua branch)
git add .

git commit -m <msg>

git push origin <nome da sua branch>


# Fazer merge da sua branch com o main

git checkout main

git pull origin main

git merge --no-ff <branch>

( até aqui pode ter dado conflito ou não )
(caso não tenha dado, segue assim:)
git push origin main

git checkout <branch>

git pull origin main

git push origin <branch>

(caso tenha dado conflito:)
(corrigir conflitos e depois:)

git commit -m <msg>

git push origin main

git checkout <branch>

git pull origin main

git push origin <branch>

# GIT SSH
eval "$(ssh-agent)"

ssh-add
