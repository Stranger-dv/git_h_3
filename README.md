# Git

# H-3 (Hacer merge en mi master local y luego con master remoto)

## Comandos utilizados
```
git init
git remote add origin (pegar_la_ruta_del_repositorio_local)
git remote -v
touch menu_de_comidas
ls -l
git status
git add .
git status
git commit -m "feat: add menu_de_comidas.txt"
git log --oneline
git push -u origin master
git branch feature/agregarComidas
git branch
git switch feature/agregarComidas
echo -e "arroz, pan, pizza" >> menu_de_comidas.txt
cat menu_de_comidas.txt
git status
git add .
git status
git commit -m "feat: add content in menu_de_comidas.txt"
git log --oneline
git switch master
git branch 
git merge feature/agregarComidas
git push -u origin master
git branch
git branch -D feature/agregarComidas
git branch
```
