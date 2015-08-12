## Code.education - Curso GIT - Projeto Fase 1 - Fazendo o primeiro push

** - Principais instruções**

git init<br />
touch arquivo.txt
vim arquivo.txt
touch README.md
vim README.md
git status
git add arquivo.txt
git commit -m "Meu primeiro commit"
git status
git log
vim arquivo.txt
git status
git add README.md
git add arquivo.txt
git status
git commit -m "Alterando o arquivo.txt"
git status
git log
vim teste.php
git status
git add teste.php
git status
git commit
git log
vim arquivo.txt
vim teste.php
git status
git commit -a -m "Commitando arquivo e teste juntos"
mkdir .idea
touch .idea/teste
git status
vim .gitignore
git status
git add .
git commit -m "Adicionando .gitignore"
git log
git status
touch teste2.txt
git add teste2.txt
git reset HEAD teste2.txt
touch teste3.txt
touch teste4.txt
git add .
git reset HEAD teste2.txt
git reset HEAD teste3.txt
git reset HEAD teste4.txt
git checkout 5c61690bc26004d8eb0462c3dac555923a0b08e3
git branch
git reset HEAD~1 --soft
git commit -m "Colocando .gitignore"
git reset HEAD~1 --hard
git checkout -b funcionalidade1
git add funcionalidade1.txt
git commit -m "Adicionando funcionalidade 1"
git checkout master
git add arquivo.txt
git commit -m "Modificando arquivo.txt"
git merge funcionalidade1
git reset HEAD~1 --hard
git rebase funcionalidade1
git branch -d funcionalidade1

git remote add origin https://github.com/marcusvar/aulagit.git

