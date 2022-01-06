# 1. Setup

Para contribuir a un proyecto de GitHub, necesitará dos cosas: un Fork de GitHub y un clon local de este proyecto.

## :running: Activities

Siga las actividades a continuación para prepararse para el resto del tutorial.

### 1 - Fork a Source Repository

__All Team Members__

Fork the source repository:
   1. Visita https://github.com/m-salcedo/libro-git.
   2. Click en el botón "fork", y elija su cuenta personal de GitHub si se le solicita.

---

:cop: :raised_hand: - Por favor espera hasta que todo se hayan puesto al día.

:construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction:

---

### 2 - Clone your Fork

__All Team Members__

Clona este proyecto en tu máquina local:
```sh
$ cd ~/my/parent/directory
$ git clone https://github.com/tu-nombre/libro-git.git
# clona el repositorio de la bifurcación de GitHub

$ cd repository-name
# cambiar el directorio de trabajo al repositorio clonado
```

Ver controles remotos existentes:
```sh
$ git remote
origin

$ git remote -v
origin https://github.com/source-username/repository-name.git (fetch)
origin https://github.com/source-username/repository-name.git (push)
```

Debería ver un control remoto `origin` que apunta al proyecto de GitHub de origen:
```sh
$ git remote show origin
* remote origin
  Fetch URL: https://github.com/source-username/repository-name.git
  Push  URL: https://github.com/source-username/repository-name.git
  HEAD branch: master
  Remote branches:
    develop tracked
    master  tracked
  Local branch configured for 'git pull':
    master  merges with remote master
  Local ref configured for 'git push':
    master  pushes to master (up to date)
```


# Una vez culminado el setup, dirígete a la raíz del proyecto e inicia los comandos:

## Ejercicio 1
Crear una nueva rama feature bibliografia.

## Ejercicio 2
Crear un archivo en la siguiente dirección: capitulos/capitulo4.txt y añadir el texto siguiente
“En este capítulo veremos cómo usar GitFlow para alojar repositorios en remoto.”

Hacer un commit con el mensaje “Añadido capítulo 4.

## Ejercicio 3
Cambiar a la rama feature/bibliografia.
Crear el fichero bibliografia.txt y añadir la siguiente referencia
“Chacon, S. and Straub, B. Pro Git. Apress.”

Hacer un commit con el mensaje “Añadida primera referencia bibliográfica.”

## Ejercicio 4
Crear nueva rama release v1.x.x

Añade un archivo que se llame versionado.txt y escribele
"Esta es la versión 1.0.0"

Finaliza la rama release.

## Ejercicio 5

Crear una nueva rama hotfix bibliografia desde release/v1.x.x
Cambiar a la rama hotfix/bibliografia.

Cambiar el archivo bibliografia.txt para que contenga las siguientes referencias:
“Scott Chacon and Ben Straub. Pro Git. Apress.
Ryan Hodson. Ry’s Git Tutorial. Smashwords (2014)”

Cambiar el archivo versionado.txt para que contenga :
"Esta es la versión 1.0.1"

hacer un commit con el mensaje “Modificada la referencia bibliográfica.”

### finalizar hotfix.

