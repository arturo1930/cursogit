# Capacitación GIT


## Comandos basicos de git

```
git init: Inicializa un repositorio Git en un directorio existente.
git clone <repo>: Clona un repositorio remoto en su máquina local.
git add <file>: Agrega un archivo al área de preparación para la confirmación.
git commit -m "<message>": Confirma los cambios en el repositorio local con un mensaje de descripción.
git push: Envía los cambios confirmados al repositorio remoto.
git pull: Descarga los cambios del repositorio remoto a su máquina local.
git branch <branch_name>: Crea una nueva rama.
git checkout <branch_name>: Cambia a una rama existente.
git merge <branch_name>: Fusiona una rama con la rama actual.
git log: Muestra un historial de confirmaciones en el repositorio.
```


## Comandos avanzados de git
```
git stash: Guarda temporalmente los cambios no confirmados para poder cambiar a otra rama.
git rebase: Reaplica las confirmaciones de una rama sobre otra.
git cherry-pick: Aplica una confirmación específica de una rama a la rama actual.
git reset: Deshace los cambios en el área de preparación y el directorio de trabajo.
git revert: Deshace una confirmación específica y crea una nueva confirmación con los cambios revertidos.
git bisect: Realiza una búsqueda binaria en el historial de confirmaciones para encontrar una confirmación específica.
git submodule: Agrega un repositorio Git como un módulo de otro repositorio.
git reflog: Muestra un historial de referencias en el repositorio.
git fsck: Verifica la integridad de los objetos y referencias en el repositorio.
```

## Crear proyecto desde 0

Este es un ejemplo de cómo crear un proyecto desde cero hasta hacer un git pull en Git:

Cree una carpeta para su proyecto y cámbiese a esa carpeta en su terminal:
```
$ mkdir mi_proyecto
$ cd mi_proyecto
```
Inicialice un repositorio Git en la carpeta:
```
$ git init
```
Cree un archivo de texto y agréguelo al repositorio:
```
$ echo "Mi archivo de texto" > archivo.txt
$ git add archivo.txt
$ git commit -m "Agregar archivo de texto"
```
Cree un repositorio remoto en un servicio como GitHub y siga las instrucciones para vincularlo con su repositorio local:
```
$ git remote add origin <url_del_repositorio_remoto>
$ git push -u origin master
```
Supongamos que otro colaborador ha hecho cambios en el repositorio remoto y quieres traer esos cambios a tu máquina local. Puedes hacer un git pull:
```
$ git pull origin master
```
Ahora deberías tener los cambios más recientes en tu máquina local.
