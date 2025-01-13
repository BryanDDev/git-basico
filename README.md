#comandos utiles git

1. git init 
2. git add . #añade al repositorio 
3. git reset . #cancela lo del git add 
4.  git commit -m
5.  git checkout -- . # recuperar contenido
6.  git log
7. git commit --amend #modificar el titulo de mis commit 
8.  git checkout -b rama-heroes
9.  git checkout main
10.  git branch # para saber en que rama estoy
11.  git branch -d nombre de la rama #borra la rama q ta no necesitemos
12. git push
13. git commit -am 
14. git push origin main #hace el psuh a mi main de git hub

-------------------------------------------------------
-- Subir una carpeta o archivo --
1. cd ruta de la carpeta o archivo que quiera subir
2. git add nombre de la carpeta o archivo
3. git commit -m
4. git push origin main

-- Eliminar una carpeta o archivo en local y que se actualice en git-- \

1. cd ruta de la carpeta o archivo que quiera subir
2. rm -r nombre_de_tu_carpeta #Para carpeta
3. rm nombre_de_tu_archivo #Para archivo
4. git add -u
5. git commit -m "Eliminar carpeta/archivo innecesario"
6. git push origin main
 -------------------------------------------------------