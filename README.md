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




⚠️ para crear una rama minimo tiene que tener un commit en el repositorio

# clase 3
## Fusionar ramas
Cuando hablamos de fusión nos referimos a que los cambios que hemos realizado en la rama se integra otra rama

<p align="center">
  <img src="https://github.com/user-attachments/assets/d2c96de5-0adf-4e80-8ca2-f4dd279c8c94" alt="image" />
</p>




* **git brach --delete<nombredelarama>**
* **git branch -d<nombredelarama>**
## ¿Por que eliminar ramas?
Se la elimina cuando ya no las necesita, como después de fusionarlas 
Así evito confusiones, mantengo el repositorio limpio y organizado.
Además, ayuda a que otros no trabajen por error en ramas viejas o innecesarias se la elimina con
* **git branch --delete <elnombredelarama>**
## conflictos en Git
**1**
borrar un archivo por accidente
* **solucion**
  git restore archivo
  git log

**2**
  conflictos con el merge
  * **solucion**
    git add archivo
    git commit

    **esas fueron las que me sucedieron a mi XD**

# Clase 4
## Empezamos con GitHub <img src="https://github.com/user-attachments/assets/ecd23cd3-f833-4736-bc56-2bd3d3a7c5d1" alt="GitHub logo" width="80" style="vertical-align: middle;">

GitHub es como una red social para proyectos de programación. Me permite guardar mi código en la nube, trabajar en equipo, y llevar el control de todos los cambios que hago con Git. Básicamente, uso Git en mi compu para manejar versiones del código, y luego uso GitHub para subir todo eso a internet y colaborar con otros. 

## ¿Git y GitHub son los mismos?

![image](https://github.com/user-attachments/assets/267ec2a2-0397-4f57-aaf0-f2f5115ab2a9)



Git y GitHub no son lo mismo, aunque se usan juntos casi siempre.
Git es una herramienta que tengo instalada en mi compu y me sirve para guardar los cambios que voy haciendo en mi código, llevar un control de versiones, y no perder nada si rompo algo. Todo eso lo hago de forma local, sin necesidad de internet.

En cambio, GitHub es una página web donde puedo subir esos proyectos que manejo con Git, para tenerlos en la nube, compartirlos con otros y trabajar en equipo. Es como el “Google Drive” de los proyectos de código, pero mucho más pro porque tiene herramientas para colaborar, revisar cambios, automatizar tareas, y más.

En resumen: Git es la herramienta, y GitHub es el lugar donde subo lo que hago con esa herramienta.

## ¿GitHub es único?
no es el  unico pero si es el mas popular pero esxisteno otras como

| 🚀 Plataforma     | 🔎 ¿Qué ofrece?                                                                 |
|------------------|----------------------------------------------------------------------------------|
| **GitHub**        | La más conocida, con muchas herramientas para colaboración y automatización.   |
| **GitLab**        | Muy completo, permite tener repos privados gratis y tiene CI/CD integrado.     |
| **Bitbucket**     | Integrado con Atlassian (como Jira), muy usado en entornos empresariales.      |
| **SourceForge**   | Más antigua, orientada a proyectos de código abierto (open source).            |
| **Azure DevOps**  | De Microsoft, muy útil para gestionar código, tareas y despliegues.            |


## Como se usa un repositorio remoto (elemplo en GitHub)
* **¿Como se usa GitHub?**
**1.-**   Primero tenemos que crear un repositorio en GitHub
**2.-**   Luego abro una terminal ("en bash git") y se escrive
como se ve en la imagen esos son los codigos que se usan
  ![image](https://github.com/user-attachments/assets/2ffd3cb9-8e6c-4f08-bd00-26f8a4b215d2)
  ![image](https://github.com/user-attachments/assets/4dcaa351-4a32-4a47-9342-20b38d4acfd4)
y tu git se veria haci y tendria los datos que tenias en tu codigo --En mi caso seria en pruebas--
![image](https://github.com/user-attachments/assets/a88a1af4-4312-40d6-a8ea-67f2f6fb925a)

## Para que sirve cada uno de los comandos
<details><summary>ABREME!!!!! para mas info 😎😎</summary>

### Comandos

| **Comando**                                                                   | **Descripción**                                                                                                                |
|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| `git init`                                                                     | Inicializa un repositorio Git en la carpeta local, preparándolo para empezar a realizar seguimientos de cambios.               |
| `git add .`                                                                    | Agrega **todos los archivos** modificados al área de preparación (staging area) para ser incluidos en el próximo commit.        |
| `git commit -m "primer commit"`                                                | Crea un commit con un mensaje descriptivo que guarda el estado actual del repositorio.                                         |
| `git remote add origin https://github.com/1Godoy123/scesi.git`                 | Conecta tu repositorio local con el repositorio remoto de GitHub, permitiendo sincronización de archivos entre ambos.           |
| `git push -u origin main`                                                      | Empuja los cambios locales de la rama `main` hacia el repositorio remoto en GitHub. El `-u` establece la relación para futuros `push`. |

</details>

* **Podemos veer informacion de otras personas pero como es algo izi y no quiero llena mucho espacio enbano entonces no lo mostrare solo mostrare como se ve  el perfil de una persona XD



## ![image](https://github.com/user-attachments/assets/f457d08e-cc91-4ec2-ad3b-8642912f024b)

## como clonar un repositorio
|comando    | descripcion|
|------------------|--------------|
|git clone "https://github.com/usuario/repositorio.git"   |     Clona un repositorio remoto de GitHub en tu máquina local. Solo necesitas reemplazar la URL con la del repositorio que deseas clonar.|
|cd repositorio          |   Entra en la carpeta del repositorio recién clonado, para empezar a trabajar en él.|

## Como escrivir en un repositorio remoto 
para hacer esto tienes que tener actualizado el bash
* **git add .**
Después de hacer los cambios, agrega los archivos modificados al área de preparación (staging area).

* **git commit -m "Descripción de los cambios"**
Realiza un commit con un mensaje que explique los cambios que hiciste.

* **git push origin main**
Finalmente, sube los cambios al repositorio remoto en la rama main. Si estás trabajando con otra rama, reemplaza main con el nombre de tu rama.

## Como crear una rama remota

* **git checkout -b nombre-de-tu-rama**
Esto crea una nueva rama y te cambia automáticamente a ella. Reemplaza nombre-de-tu-rama por el nombre que desees para la nueva rama.

Luego, subes esa rama al repositorio remoto con:

* **git push origin nombre-de-tu-rama**
Esto sube la nueva rama a GitHub o a tu repositorio remoto! 😲✨.

| **git**       | **Para qué sirve**                                                                                                                                                                           |
|---------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **git pull**  | **Función**: Descargar los cambios del repositorio remoto y actualizar tu repositorio local con esos cambios. <br> **Dirección de los cambios**: Va de remoto a local. <br> **Cuándo usarlo**: Lo usas cuando quieres obtener los cambios que otras personas han subido al repositorio remoto (por ejemplo, en GitHub) para tener la versión más reciente del proyecto en tu máquina local. <br> **Ejemplo**: Si otros colaboradores han hecho cambios en la rama `main` en GitHub y quieres obtener esos cambios en tu repositorio local, usas `git pull`. |
| **git push**  | **Función**: Subir los cambios de tu repositorio local al repositorio remoto. <br> **Dirección de los cambios**: Va de local a remoto. <br> **Cuándo usarlo**: Lo usas cuando has hecho cambios en tu repositorio local (como agregar archivos, modificar código) y quieres compartir esos cambios con otras personas o guardarlos en el repositorio remoto (como GitHub). <br> **Ejemplo**: Después de hacer un commit con tus cambios, usas `git push` para subir esos cambios al repositorio remoto. |

<details><summary> Comandos de git pull❓❓❓ </summary>

| **Comando**                                       | **Descripción**                                                                                                                           |
|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| `git pull origin main`                            | **Función**: Descarga los cambios de la rama `main` del repositorio remoto (por ejemplo, en GitHub) y los fusiona con tu rama local.       |
| `git pull origin nombre-de-la-rama`               | **Función**: Trae los cambios de la rama remota `nombre-de-la-rama` y los fusiona con tu rama local.                                        |
| `git pull nombre-del-remoto nombre-de-la-rama`    | **Función**: Si tienes más de un repositorio remoto configurado, especifica desde qué remoto deseas hacer el pull.                        |
| `git pull --no-commit origin main`                | **Función**: Trae los cambios de la rama `main`, pero **no hace el commit automáticamente**. Puedes revisar antes de confirmar el merge. |
| `git pull --rebase origin main`                   | **Función**: Aplica tus cambios encima de los cambios del remoto en lugar de hacer un merge, manteniendo un historial más limpio.          |
</details>

<details><summary> Comandos de git push❓❓❓ </summary>

| **Comando**                                       | **Descripción**                                                                                                                           |
|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| `git push origin main`                            | **Función**: Sube los cambios locales de la rama `main` al repositorio remoto (por ejemplo, en GitHub).                                     |
| `git push origin nombre-de-la-rama`               | **Función**: Sube los cambios locales de la rama `nombre-de-la-rama` al repositorio remoto.                                                |
| `git push --set-upstream origin nombre-de-la-rama`| **Función**: Establece la rama remota como el origen para la rama local, útil cuando creas una nueva rama local y la subes por primera vez. |
| `git push origin --delete nombre-de-la-rama`      | **Función**: Elimina la rama `nombre-de-la-rama` del repositorio remoto.                                                                  |
| `git push -u origin main`                         | **Función**: Sube los cambios de la rama `main` y establece una relación de seguimiento con la rama remota, facilitando futuros `push`.    |
</details>

## Que es un PR
Un Pull Request (PR) es como cuando terminas de hacer cambios en tu proyecto y quieres que otras personas los vean antes de agregarlo a la versión principal. Así que, cuando trabajo en una rama diferente (digamos que en una nueva idea o característica) y quiero que esos cambios lleguen a la rama principa

| **Comando**                                      | **¿Para qué sirve?**                                                                                   |
|--------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| `git checkout main`                              | Me aseguro de estar en la rama principal antes de crear una nueva rama.                               |
| `git pull origin main`                           | Actualizo mi rama principal local con los últimos cambios del repositorio remoto.                     |
| `git checkout -b nombre-de-mi-rama`              | Creo una nueva rama a partir de `main` para trabajar mis cambios.                                     |
| *(Aquí edito archivos normalmente)*              | Hago los cambios que quiero en el proyecto.                                                           |
| `git add .`                                      | Agrego todos los archivos modificados al área de preparación para el commit.                          |
| `git commit -m "Descripción de mis cambios"`     | Registro los cambios que hice con un mensaje descriptivo.                                             |
| `git push origin nombre-de-mi-rama`              | Subo mi nueva rama y los cambios al repositorio remoto (GitHub, por ejemplo).                         |

# Clase 5 
##¿Que es GitFlow?
Git Flow es una estrategia para organizar el trabajo en Git.
Uso la rama "main" para el código en producción estable.
La rama "develo"2 es donde integro lo que está en desarrollo.
Cada nueva funcionalidad la hago en una rama "feature".
Cuando ya casi termino, uso una rama "release" para pulir detalles.
Si hay errores urgentes, los arreglo con una rama "hotfix".
Todo sigue un flujo claro que evita el caos en el proyecto.
Así trabajo en equipo sin pisarnos el código ni romper nada.
<details><summary> Comandos de Git Flow 🚀 </summary>

| **Comando**                             | **Descripción**                                                                                           |
|----------------------------------------|-----------------------------------------------------------------------------------------------------------|
| `git flow init`                        | **Función**: Inicializa Git Flow en tu repositorio, creando las ramas base como `main` y `develop`.       |
| `git flow feature start nombre`        | **Función**: Crea una nueva rama `feature/nombre` desde `develop` para trabajar en una nueva funcionalidad.|
| `git flow feature finish nombre`       | **Función**: Fusiona la rama `feature/nombre` a `develop` y la elimina cuando terminas la funcionalidad.  |
| `git flow release start vX.X.X`        | **Función**: Crea una rama `release` desde `develop` para preparar una nueva versión.                     |
| `git flow release finish vX.X.X`       | **Función**: Fusiona `release` en `main` y `develop`, y crea un tag con la versión.                       |
| `git flow hotfix start nombre`         | **Función**: Crea una rama `hotfix` desde `main` para corregir errores urgentes en producción.            |
| `git flow hotfix finish nombre`        | **Función**: Fusiona la `hotfix` en `main` y `develop`, y etiqueta una nueva versión si es necesario.     |
| `git flow support start nombre`        | **Función**: (Opcional) Para mantener versiones antiguas que aún se deben actualizar o mantener.         |

</details> 
## ¿Que es Trunk Based Development?
Trunk Based Development, que es trabajar todos sobre la misma rama principal, normalmente main.
No me complico con muchas ramas; hago cambios pequeños y los subo seguido.
Si una función no está lista, la dejo escondida con un feature toggle.
Así el código siempre está limpio, actualizado y listo para producción.

![image](https://github.com/user-attachments/assets/3836bc38-a0d2-4424-909e-1d5d869fb90c)

| **Concepto** | **¿Qué significa?**                                                                 | **¿Cuándo lo uso?**                                                                                         |
|--------------|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| `Ship`       | Hago el cambio directamente y lo subo sin pedir revisión.                            | Cuando el cambio es **muy pequeño o trivial**, y confío en que no rompe nada (ej. corrección de typo).     |
| `Show`       | Hago el cambio y lo comparto, pero **no pido aprobación**, solo comentarios.         | Cuando quiero **feedback informal** sobre algo ya hecho (ej. rediseño, refactor que no afecta funcionalidad). |
| `Ask`        | Hago el cambio y **pido revisión antes de subirlo** (Pull Request o Code Review).    | Cuando el cambio es **grande, complejo o sensible**, y necesito asegurarme de que está bien hecho.          |
![image](https://github.com/user-attachments/assets/a6f8dda8-6ac0-4a2c-8f5d-a2ac1138a3e8)XD



* **Ship**
Contexto: Cambios triviales o seguros (ej. corregir un typo, actualizar comentarios).
Subo directamente sin revisión, porque no hay riesgo.

* **Show**
Contexto: Cambios ya hechos que quiero compartir para recibir feedback informal.
No necesito aprobación, pero sí me interesa lo que opinen los demás.

* **Ask**
Contexto: Cambios grandes, sensibles o que podrían romper algo.
Pido revisión antes de fusionar, abro un Pull Request y espero aprobación.

# Clase 6
## Buenas practicas en git

Las buenas prácticas en Git me ayudan a trabajar de forma ordenada y colaborativa.
Evitan errores, confusiones y conflictos cuando varios trabajamos en el mismo proyecto.
Uso commits claros para que el historial tenga sentido.
Evito subir cosas innecesarias, como archivos temporales.
Trabajo en ramas para no romper la versión principal.
Uso nombres descriptivos en las ramas (ej. feature/login).
No hago commits gigantes que mezclen muchas cosas.
Reviso bien antes de hacer merge o pull.
Hago pull seguido para no quedarme atrás del equipo.
Uso .gitignore para excluir archivos que no deben subirse.
Siempre pruebo antes de subir un cambio.
Escribo mensajes de commit que expliquen el "qué" y el "por qué".
Uso stash si tengo cambios a medio hacer pero necesito cambiar de rama.
Y antes de un push, me aseguro de que todo esté bien probado y limpio.
![image](https://github.com/user-attachments/assets/08469091-76ed-41ff-beb1-ad336b709982)


##¿Cada cuanto deveria hacer un commit?
a menudo es mejor tener commits pequeños commits para saber que hace un commit.
![image](https://github.com/user-attachments/assets/3420cec1-7548-43f0-8831-e6e5bc401ddf)
hacer un commit a menudo no significa hacerlos sin sentido
## ¿Como hacer un buen commit?
Un buen commit debe usar el modo imperativo y ser claro.
El mensaje corto debe ser directo, sin pasar de 50 caracteres.
Si es necesario, agrega un cuerpo más largo explicando qué y por qué.
El título y cuerpo deben estar separados por una línea en blanco.
No uses mensajes vagos como “cambios” o “actualización”.
Evita usar tiempo pasado, como "Agregué" o "Hice".
Sé coherente en el estilo y los detalles para que todos entiendan el historial.
Un buen commit facilita el trabajo en equipo y la depuración.

## ¿como hacer una buena rama?

Una buena rama tiene un nombre claro y descriptivo.
Usa prefijos como feature/, bugfix/ o hotfix/ para especificar el tipo de tarea.
El nombre debe ser corto, pero lo suficientemente detallado para entender el propósito.
Evita nombres genéricos como test o dev.
Usa guiones (-) para separar las palabras en lugar de guiones bajos (_).
El nombre debe reflejar el propósito del trabajo en esa rama.
Es recomendable incluir el número de la tarea o el bug si usas un sistema de seguimiento.
Siempre parte de la rama principal (main o develop) para evitar conflictos.

# Clase 7
## En que casos desasemos cambios?
*  Cuando cometiste un error en el código.
Si cometiste un error y ya hiciste un commit, puedes deshacerlo sin afectar el historial del repositorio.

*  Cuando agregaste archivos innecesarios al repositorio.
Si accidentalmente agregaste archivos que no deberían estar en el repo (como archivos de configuración locales), puedes eliminarlos fácilmente.

*  Cuando hiciste cambios sin querer y no has hecho un commit.
Si ya modificaste archivos pero no has realizado un commit, puedes simplemente revertir los cambios locales.

* Cuando intentas hacer un merge que resulta en conflictos que no puedes resolver.
Si un merge genera demasiados conflictos y prefieres cancelar todo el proceso, puedes deshacerlo.


| **Comando**                                      | **Descripción**                                                                                                      |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| `git checkout -- archivo.txt`                    | **Función**: Deshace cambios no guardados en el archivo especificado, restaurando el archivo al estado del último commit.|
| `git reset --soft HEAD~1`                        | **Función**: Deshace el último commit pero **mantiene los cambios** en tu área de trabajo para poder editarlos.       |
| `git reset --hard HEAD~1`                        | **Función**: Deshace el último commit y **descarta todos los cambios** en los archivos, restaurando todo al último commit.|
| `git rm --cached archivo.txt`                    | **Función**: Elimina el archivo del seguimiento de Git (pero lo deja en tu sistema de archivos). Es útil para eliminar archivos innecesarios.|
| `git commit -m "Elimina archivo innecesario"`    | **Función**: Después de usar `git rm --cached`, este commit elimina el archivo de Git, pero lo mantiene localmente.    |

## Comando destructivos y no destructivos

| **Tipo**               | **Comando**                                      | **Descripción**                                                                                                      |
|------------------------|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| **No Destructivo**      | `git status`                                    | **Función**: Muestra los cambios actuales en tu área de trabajo, sin modificar nada.                                 |
| **No Destructivo**      | `git diff`                                      | **Función**: Muestra las diferencias entre el estado actual de los archivos y el último commit, sin afectar nada.     |
| **No Destructivo**      | `git commit`                                    | **Función**: Realiza un commit de los cambios, guardándolos en el historial. No afecta el historial previo.          |
| **Destructivo**         | `git reset --hard`                              | **Función**: Deshace los commits, y **elimina los cambios locales** sin posibilidad de recuperación.                  |
| **Destructivo**         | `git clean -f`                                  | **Función**: Elimina archivos no rastreados en el directorio de trabajo, como archivos temporales o generados.        |
| **Destructivo**         | `git push --force`                              | **Función**: Sobrescribe la historia del repositorio remoto, eliminando o modificando commits previos (peligroso).    |

![Explosión de Calamardo](https://i.makeagif.com/media/10-02-2015/nftfX2.gif)
## ¿Qué hace git revert?
No elimina el commit original, sino que crea un nuevo commit que revierte los cambios del commit especificado.

Se usa cuando deseas deshacer los efectos de un commit pero sin perder el historial de ese cambio.

¿Cuándo usarlo?
Cuando ya has compartido el commit con otras personas (por ejemplo, en un repositorio remoto) y no quieres reescribir el historial.
## ¿Qué hace git checkout?
Cambiar de rama:
Cuando usas git checkout con el nombre de una rama, cambias a esa rama en tu repositorio local.

## codigos
|**codigos**                                         |  **Descripción**                                                                                    |
|----------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| `git checkout <nombre-de-la-rama>`                 | **Función**: Cambia a la rama especificada.                                                                                 |
| `git checkout -b <nombre-de-la-nueva-rama>`        | **Función**: Crea una nueva rama y cambia a ella.                                                                          |
| `git checkout -- <archivo>`                        | **Función**: Restaura un archivo a su estado en el último commit, deshaciendo cambios no comprometidos.                   |
| `git checkout <rama> -- <archivo>`                 | **Función**: Restaura un archivo desde otra rama sin cambiar de rama completamente.                                        |
| `git checkout <hash-del-commit> -- <archivo>`      | **Función**: Restaura un archivo desde un commit específico, permitiendo deshacer cambios a un punto anterior.            |
| `git checkout main`                                | **Función**: Cambia a la rama principal (típicamente `main` o `master`).                                                 |

# Clase 8
## ¿Que es hook?
Un hook en Git es un script que se ejecuta automáticamente cuando ocurre un evento específico dentro del ciclo de vida de Git (como un commit, push, merge, etc.).

|**Códigos**            |**Función / Descripción**                                                                 |
|-----------------------|------------------------------------------------------------------------------------------|
|`pre-commit`           |**Función**: Se ejecuta antes de hacer `git commit`. Ideal para correr tests o linters.  |
|`commit-msg`           |**Función**: Después de escribir el mensaje del commit. Verifica convención como `feat:`.|
|`pre-push`             |**Función**: Antes de hacer `git push`. Revisa tests o errores antes de subir cambios.   |
|`post-merge`           |**Función**: Después de un `git merge`. Útil para actualizar dependencias o reiniciar.   |
|`pre-rebase`           |**Función**: Antes de ejecutar `git rebase`. Valida el estado limpio del repositorio.    |

🧠 ¿Qué son los alias en Git?
Los alias en Git son como atajos personalizados que te permiten ejecutar comandos largos o complejos con nombres más cortos o intuitivos.


<details><summary> comandos de alias </summary>

|**Alias / Comando**                      |**Función / Descripción**                                                                 |
|-----------------------------------------|------------------------------------------------------------------------------------------|
|`git st`                                 |**Alias** de `git status`. Muestra el estado del repositorio.                           |
|`git co <rama>`                          |**Alias** de `git checkout <rama>`. Cambia de rama fácilmente.                          |
|`git br`                                 |**Alias** de `git branch`. Lista todas las ramas.                                       |
|`git hist`                               |Muestra el historial con grafo y commits resumidos.                                     |
|`git ci -m "mensaje"`                    |**Alias** de `git commit -m`. Hace commits rápidos.                                     |
|`git last`                               |Muestra el último commit hecho.                                                         |
|`git type`                               |Muestra el tipo de cada archivo con `ls-tree`. Útil para revisar estructura.            |
|`git unstage <archivo>`                 |Deshace un `git add`, dejando el archivo sin preparar.                                  |
|`git amend`                              |Edita el último commit sin cambiar el historial (si no ha sido pusheado).               |
|`git lg`                                 |Muestra un log visual completo (similar a `hist`). Ideal para ver ramas y merges.       |
|`git cleanup`                            |Alias personalizado para eliminar ramas locales ya fusionadas.                         |
</details>



<details><summary> Comandos de para acortar codigos </summary>

|**Truco / Comando**                                       |**Función / Descripción**                                                                 |
|-----------------------------------------------------------|------------------------------------------------------------------------------------------|
|`git log -S"texto"`                                       |🔍 Busca commits que hayan agregado o eliminado cierto texto.                            |
|`git diff main..HEAD`                                     |📌 Muestra diferencias entre tu rama actual y `main`.                                    |
|`git checkout HEAD -- archivo.txt`                        |♻️ Restaura un archivo al estado del último commit.                                      |
|`git branch --merged \| grep -v "\*" \| xargs git branch -d`|🧹 Elimina ramas locales ya fusionadas.                                                   |
|`git log -n 5 --name-only --pretty=format:`               |📂 Muestra archivos modificados en los últimos 5 commits.                                |
|`git reflog`                                              |📜 Muestra todos los movimientos de HEAD, útil para recuperar commits perdidos.          |
|`git stash`                                               |👜 Guarda temporalmente los cambios no guardados para cambiar de rama sin perderlos.     |
|`git stash pop`                                           |📤 Restaura los cambios guardados con `stash`.                                           |
|`git cherry -v main`                                      |🍒 Muestra commits únicos en tu rama que no están en `main`.                            |
|`git shortlog -sn`                                        |👥 Muestra los autores y cuántos commits ha hecho cada uno.                             |
</details>
 
## Notaaaaaaa 
Con esto acabo mi proyecto en github con ganas de querer aprobar pero veremos que pasa con el tiempo gracias por ver y adios..

# 9/mayo/2025
