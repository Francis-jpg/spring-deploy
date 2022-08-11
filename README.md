## Despligue de apps Spring Boot en heroku
Crear achivo 'syste.properties' en el proyecto con el contenido:

.....
java.runtime.version=17
....

1. Crear cuenta en heroku.com y github.com
2. Terne configurado git en el ordenador
    1. 'git config --global user.name "Francisco Molina"'
    2. 'git config --global user.email francisco.fm34@example.com'
3. subir el proyecto a GitHub desde Intellij IDEA desde la opción : VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir GitHub y buscar el repositorio subido 
5. Habilitar deploy automáticamente y ejecutar el Deploy

