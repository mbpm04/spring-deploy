
## Despliegue de apps Spring Boot en Heroku

Crear archivo "system.properties" en el proyecto conm el contenido:

"""
java.runtime.version=17
"""


1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
   1. git config --global user.name "Benjamin Pedernera"
   2. git config --global user.email benjapedernera2004@gmail.com
3. Subir el proyecto a GitHub desde IntelliJ IDEA desde la opción: VCS > Share project in GitHub
4. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar Deploy automático y ejecutar el Deploy