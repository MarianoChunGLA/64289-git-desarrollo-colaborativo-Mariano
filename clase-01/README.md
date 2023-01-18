## GIT Desarrollo colaborativo

## Clase 01


## Areas en GIT

* Working Directory (WD): Es el area de trabajo

* Staging Area (SA): Area temporal de confirmación de cambios, previo al commit
(Foto del código).

* Local Repo (LR): Caja de commits. Aca voy a tener todos los commits que le vaya haciendo al código 

## Configurar GIT
```sh
git config --global user.name "Nombre Apellido"

git config --global user.email "example@gmail.com"
```

### Ayuda del comando CONFIG
```sh
git config --help
```

## Listado de configuraciones
```sh
git config --list
```

## Inicializar o crear repo
git init

## Estado de los archivos dentro del repo

* Untracked: Archivos desconocidos por el repositorio
* Unmodified: Archivos conocidos por el repo, pero que no sufrieron cambios desde el último commit
* Modified: Archivos conocidos por el repo, y  a su vez, fueron modificados
* Staged: Archivos cuyos cambios fueron confirmados por nosotros