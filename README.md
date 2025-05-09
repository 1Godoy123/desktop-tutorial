<h1>
  Curso de Git y GitHub
  <a href="https://github.com">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo GitHub" width="40" style="vertical-align: middle; margin-left: 10px;">
  </a>
</h1>

# Clase 1

## ¿Qué es un control de verciones❓❓❓
es un sistema que registra todos los cambios en el codigo fuente de un proyecto

## ¿Por que es importante un control de versiones?
*  **rendimiento⚡** guarda lo que es importante
*  **seguridad🔒** conserva lo que le pidas
*  **flexibilidad🔁** no es nesesario un desarrollo
    ![image](https://github.com/user-attachments/assets/3ad0239d-def8-4ee1-8472-fadc65e961f7)>
  
## ¿Que es git?  

<img src="https://github.com/user-attachments/assets/e6a6ec1f-b1c9-47f7-bae5-ac4f63ac34b0" align="right"
alt="Git Logo" width="110" height="110">

Un sistema de control de versiones distribuido, aloja una copia completa del repositorio ennuestra maquina local para que posteriormente podamos subirlo a un repositorio remoto y podamos hacer trabajo colaborativo
  
¿Qué es un repositorio?

Es una especie de almacen para guardar los archivos, se podria ver como un estante para libros

<p align="center">
  <img src="https://github.com/user-attachments/assets/38b71276-a672-4a82-a2d8-4c56796a2354" alt="image" />
</p>


## ¿como instalar Git?

Para instalar Git, primero voy a la página oficial git-scm.com y descargo la versión para mi sistema operativo.
Luego simplemente sigo los pasos del instalador, dejando las opciones por defecto.
Cuando termina, abro la terminal y escribo git --version para comprobar que quedó bien instalado.

# Clase 2
 ## los 3 estados de Git 

Estado      |Descripción|
|-------------|:------------|
|Modified|El archivo se creo, elimino o contiene un cambio que no se confirmo|
|Staged|Ha sido confirmado en el repositorio local|
|Commited|El archivo esta grabado en el repositorio local|

## Comandos y para qué sirven
<details><summary>Iniciando un proyecto en Git </summary>

### Comandos básicos de Git
| Comando | Utilidad |
|--------|----------|
| `git init` | Inicia un nuevo repositorio en la carpeta actual |
| `git status` | Muestra el estado de los archivos |
| `git add *archivo` | Prepara un archivo para ser confirmado |
| `git commit -m "mensaje"` | Guarda los cambios preparados con un mensaje descriptivo |
| `git log` | Muestra el historial de commits |
| `git branch` | Lista todas las ramas en el repositorio |
| `git switch *rama` | Cambia a otra rama existente |
| `git push` | Sube los cambios al repositorio remoto |
| `git pull` | Descarga y combina los cambios del repositorio remoto |

</details>



## ¿Qué es Commit?
Es tipo  punto de guardado, como sacar imagenes cada 2 minutos y ver que cambio tuviste pasando dos minutos o para mejor explicacion en un videojuego se puede guardar una o mas partidas para continuar desde ese punto el juego  un claro ejemplo seria vice city

<p align="center">
  <img src="https://github.com/user-attachments/assets/c45b1301-9d73-4ce8-9b5a-d2a954958a78" alt="image" />
</p>


 
## ¿Qué es HEAD?
Es como un tipo de ubicacion para saber donde te ubicas   
Este marca el commit en el que te encuentras actualmente y puedes verlo con un git log

# ¿Qué es una rama?
Es una versión separada del repositorio principalal ser una linea de desarollo independientemente cualquier cambio que se haga en la rama se mantendra separado de las demas

<p align="center">
  <img src="https://github.com/user-attachments/assets/207b5104-c66d-499a-9d93-592c16566eb3" alt="a5" />
</p>




⚠️ para crear una rama minimo tiene sque tener un commit en el repositorio

