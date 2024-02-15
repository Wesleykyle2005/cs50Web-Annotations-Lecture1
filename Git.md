
# Concepto

[Git](https://git-scm.com/) es un sistema de control de versiones distribuido gratuito y de código abierto diseñado para manejar todo, desde proyectos pequeños hasta proyectos muy grandes con velocidad y eficiencia. 

Github es un sitio donde uno puede alojar los proyectos realizados y además facilita el trabajo en equipo y su realización.
## Inicio en github

* Descargar git [Download](https://git-scm.com/downloads)
* Crear una cuenta de github [Click](https://github.com/signup?source=login)
* Crear un nuevo repositorio
## Comandos útiles

1. Clonar un repositorio: `git clone (URL del repositorio)`
2. Añadir archivos al registro de cambios: 
   - `git add (nombre del archivo 1) (nombre del archivo 2)` 
   - o simplemente `git add .`
3. Guardar cambios realizados: `git commit -m "descripción del cambio"`
4. Combinar `git add` y `git commit`: `git commit -am "descripción"`
5. Enviar cambios al repositorio remoto: `git push`
6. Traer cambios del repositorio remoto: `git pull`
7. Deshacer un cambio: `git reset --hard <nombre del commit>`
8. Crear una nueva rama:
   - `git checkout -b <nombre de la nueva rama>` 
   - o simplemente `git checkout <nombre de la rama>` si ya existe
9. Combinar cambios de una rama en otra: `git merge (nombre de la otra rama)`

## Otras funciones de github

1. **Forking (Clonar):** Como usuario de GitHub, tienes la capacidad de clonar cualquier repositorio al que tengas acceso, lo que crea una copia del repositorio del que eres propietario. Esto se hace haciendo clic en el botón "Fork" en la esquina superior derecha.
   
2. **Pull Requests (Solicitudes de extracción):** Una vez que hayas clonado un repositorio y hayas realizado algunos cambios en tu versión, es posible que desees solicitar que esos cambios se agreguen a la versión principal del repositorio. Por ejemplo, si quisieras agregar una nueva función a Bootstrap, podrías clonar el repositorio, hacer algunos cambios y luego enviar una solicitud de extracción. Esta solicitud de extracción podría ser evaluada y posiblemente aceptada por las personas que administran el repositorio de Bootstrap. Este proceso de personas realizando algunos cambios y luego solicitando que se fusionen en un repositorio principal es vital para lo que se conoce como software de código abierto, o software que es creado por contribuciones de varios desarrolladores.

3. **GitHub Pages:** GitHub Pages es una forma sencilla de publicar un sitio estático en la web. Para hacer esto:
   - Crea un nuevo repositorio en GitHub.
   - Clona el repositorio y realiza cambios localmente, asegurándote de incluir un archivo index.html que será la página de inicio de tu sitio web.
   - Sube esos cambios a GitHub.
   - Navega hasta la página de Configuración de tu repositorio, desplázate hacia abajo hasta GitHub Pages y elige la rama principal en el menú desplegable.
   - Desplázate hacia abajo nuevamente hasta la parte de GitHub Pages de la página de configuración y, después de unos minutos, deberías ver una notificación de que "Tu sitio se publica en: ..." que incluye una URL donde puedes encontrar tu sitio.