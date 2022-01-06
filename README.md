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
