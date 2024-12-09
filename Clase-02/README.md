# Clase 2 Git Colaborativo

```sh

git restore .\Clase-02\README.md

```

## Recuperar archivos de las diferentes areas

```sh
git restores . #Recupero tod. Me traigo todo los que esta en el repo local al working directory
git restore <nombre-archivo> 
git restore --staged <nombre-archivo> #Me recuepra los cambios marcados en el staging area al working directory

```

## Modificación a modo de ejemplo. Prueba de comandos

```sh
git remote add origin https://github.com/antonelavec/73563-git.git 
git branch -M main
git push -u origin main

```