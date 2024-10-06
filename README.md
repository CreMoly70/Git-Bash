# Git-Bash
git init garcia22
git config  --global user.name "garcia22"
git config  --global user.email "cremoly70@gmail.com"
git checkout -b feature
ls
cd garcia22/
git checkout -b feature
echo "texto inicial" > archivo.txt
git add archivo.txt
git commit -m "commit inicial"
git status
echo "texto agregado en feacture" >> archivo.txt
git commit -am "segundo commit en feacture"
git checkout master
echo "tercer cambio" >> archivo.txt
git commit -am "tercer commit"
git checkout -b master
git marge feature
git merge feature
git reset --hard HEAD~1
git rebase feature
git checkout -b hotfix
echo "correcion urgente" >> archivo.txt
git commit -am "hotfix"
git checkout master
git cherry-pick hotfix
git reflog
git checkout HEAD@{9}
git checkout feature
echo "cambio en feacture" > conflicto.txt 
git add conflicto.txt
git commit -am "Cambio en feature"
git checkout master
echo "Cambio en master" > conflicto.txt
git add conflicto.txt
git commit -am "Cambio en master"
git merge feature
git status
conflicto.txt
sudo nano conflicto.txt
notepad conflicto.txt
notepad conflicto.txt
git add conflicto.txt
git commit -m "resolviendo conflicto en conflicto.txt"
git status
touch README.MD
notepad README.md
git add README.md
git commit -m "Añadir archivo README con los pasos"
ls
notepad README.MD
rm README.MD
ls
touch README.md
notepad README.md
ls
git add README.md
git commit -m "Añadiendo README con pasos"
git status
ls
touch log.txt
note pad log.txt
notepad log.txt
exit
