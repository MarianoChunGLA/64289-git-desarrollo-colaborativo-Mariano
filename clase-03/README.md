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