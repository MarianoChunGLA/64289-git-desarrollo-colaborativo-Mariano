## Clase 03

## Ramas (Branches) Continuación

## GIT SWITCH (Cambiar entre ramas)

```sh
git switch <rama>
```
> Para cambiarme entre la rama actual y la anterior

```sh
git switch -
```

> Para crear una rama y moverse a ella en un solo comando

```sh
git switch -c <nombre-rama>
```

> Ayuda del comando switch

```sh
git switch --help
```

## Subir una rama al remoto

```sh
git push -u <alias-remoto> <rama-a-subir>
## -u (sincronizacion entre rama local y rama remote)
## git push --set-upstream origin master 
git push -u origin dev
```


## GIT FETCH: Traerme metadata del repo remoto
O sea sincronizar la carpeta .git local con la .git remoto

```sh
git fetch
git fetch --all
```

## Ver todas las ramas disponibles, incluidas las del remoto en forma detallada


```sh
git branch -av # Donde -a es all y -v es verbose
```

## Puedo traerme los cambios de una rama en particular
```sh
git pull # Estando en la rama que quiero actualizar. O sea si estoy en dev, se va a actualizar con el remoto, dev
git pull origin dev
git pull origin feature
```