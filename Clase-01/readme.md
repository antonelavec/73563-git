# Git Desarrollo Colaborativo

## Markdown
Lenguaje de etiquedato para tomar apuntos, anotaciones y dar instruccion sobre el proyecto.

## Verificar que tenga instalado  GIT

```
git --version
```

## Inicializo un repositorio de git

```sh
git init # crea la carpta .git dentro del directorio/carpeta actual
```

## Configuracion inicial del GIT

```sh
git config --global user.name "Antonela Vecchio"
git config --global user.email antonelavecchio@gmail.com
```

## Verificar que la configuracion se hizo

```sh
git config --get-regexp user
```

## Como remover algo que no deseo que este

```sh
git config --global --unset xxxx
```

## Cambiar el editar a nano

```sh
git config --global corre.editor nano
```

## Cambiar el nombre por defecto de la rama principal

```sh
git config --global ini.defaulBranch main
```
