Este es un archivo de prueba para aprender a usar GIT

Cree un branch usando
```
$ git checkout -b gaston-actualiza-readme
```

y luego fui al editor de texto y meti esto en el readme, y guarde el archivo.
Luego, siempre hago
```
$ git status
On branch gaston-actualiza-readme
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   Readme.txt

no changes added to commit (use "git add" and/or "git commit -a")
```
lo que dice que cambie el archivo readme, pero no lo he commiteado.
Hice un commit para guardar este set de cambios
```
$ git commit -am "agregar al readme algunas instrucciones"
```

Luego para subir mi branch al repositorio, hice
```
$ git push origin gaston-actualiza-readme
```
y en el repositorio hice una comparacion y un pull request para pedir que lo
mezcles con lo de master.
