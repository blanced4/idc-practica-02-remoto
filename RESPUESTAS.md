# Respuestas y Reflexión - Práctica 02

## 1. Diferencia entre Git y GitHub
- **Git:** Es el sistema de control de versiones que se ejecuta de forma local en la computadora para registrar el historial de cambios, ramas y commits de un proyecto.
- **GitHub:** Es una plataforma y servicio en la nube (remoto) que permite alojar repositorios Git en Internet, facilitando el respaldo, la colaboración en equipo, revisiones de código y Pull Requests.

## 2. Diferencia entre Commit y Push
- **Commit:** Registra y confirma un conjunto de cambios en el historial local de la computadora (crea un punto de guardado local con mensaje y autor).
- **Push:** Toma los commits confirmados en el repositorio local y los transfiere/sincroniza hacia el repositorio remoto alojado en GitHub.

## 3. Diferencia entre Clone y Pull
- **Clone:** Descarga por primera vez un repositorio remoto completo desde GitHub a una computadora local, creando la carpeta, descargando todos los archivos y todo el historial de ramas.
- **Pull:** Se utiliza en un repositorio ya clonado o vinculado para descargar e integrar los cambios más recientes que existen en el repositorio remoto hacia la rama local actual.

## 4. Explicación del ejercicio "Rompe y repara"
Al ejecutar `git push` en la rama `main` sin haber creado commits nuevos locales, Git responde con el mensaje `Everything up-to-date` (Todo está al día). 
Esto **no es un error**, sino una notificación que indica que el estado de la rama local y la rama remota en GitHub están perfectamente sincronizados. Para que `push` envíe algo nuevo, tendría que existir al menos un nuevo commit confirmado en el repositorio local que aún no haya sido subido al remoto.
