
## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtine.version=17 (version actual de Java)
```

1. Crear cuenta de Heroku.com y github.com
2. Tener configurado git en el ordenador (Esto si no esta configurado aun en el ordenador)
   1. `git config --global user.name "Markitos"`
   2. `git config --global user.email marcosurrea97@hotmail.com`
3. Subir el proyecto a GitHub desde Intellij IDEA desde la opcion : VCS > share project on GitHUb
4. Desde Heroku, crear app y elegir metodo GitHub y buscar el repositorio subido
5. Habilitar depoly automatico y ejecutar el Deploy