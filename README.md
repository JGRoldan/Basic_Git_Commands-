# Basic Git Commands 

## **Work in progress** :love_you_gesture:

### Áreas y estados de los archivos
![Sin título-2023-02-28-1349](https://user-images.githubusercontent.com/71336562/222295682-d5b34913-f4bb-46e9-8d68-37ca1b699374.png)

### Comandos básicos  :pushpin:

` git init ` : _Crea un repositorio git vacio o reinicializa uno existente._

` git status ` : _Muestra el estado de los archivos._

` git add . ` : _Agrega los cambios al stage._

` git commit -m "Comentario Aca..." . ` : _Registra los cambios del repositorio local y se añade un mensaje representativo._


### Ramas y fusiones  :pushpin:

` git branch` : _Muestra las ramas existentes._

` git branch <nombre_de_rama>` : _Crea una nueva rama._

` git checkout <nombre_de_rama>` : _Pasar de una rama a otra._

` git checkout -b <nombre_de_rama>` : _Crea una nueva rama y hace switch a esa rama (Combinacion de los dos comandos de arriba)._

` git branch -m <cambiar_nombre_rama>` : _Cambia el nombre de la rama. Primero hay que ir a la rama que querramos modificar._

` git branch -m <nombre_rama_anterior> <nombre_rama_NUEVO>` : _Cambia el nombre de la rama sin tener que ir a la rama a modificar como el caso de arriba._

` git merge <nombre_de_rama_a_merge>` : _Merge a la rama PRINCIPAL (main o master). Tengo que estar en la rama con la cual quiero hacer la fusion._

` git branch -d <nombre_rama>` : _Eliminar una rama LOCAL._

` git log ` : _Muestra los ID de los commits, author & date_

` git log --oneline` : _Muestra los primeros caracteres del ID de los commits y el commit realizado en cada rama._

#### Creacion de rama y fusión con rama principal  :pushpin:

![Untitled-2023-02-05-1425](https://user-images.githubusercontent.com/71336562/222299509-11ec1b6a-91a6-4cf4-9a9e-8ef64332183a.png)

![Untitled-2023-02-05-1425](https://user-images.githubusercontent.com/71336562/222300522-ed0eb2a1-e555-4d42-b5e2-acecc87334ee.png)


### Obtener un repositorio remoto existente  :pushpin:

` git clone <link repositorio remoto>` : _Clona un repositorio remoto a un archivo local._

### Obtener rama de repositorio remoto existente  :pushpin:
` git clone --branch <nombre-rama> --single-branch URL_REPO <nombre_repo> `


