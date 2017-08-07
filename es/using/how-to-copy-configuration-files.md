# Cómo copiar los archivos de configuración
La primera tarea que debes hacer después de instalar la Consola de Drupal es ejecutar el comando `init`. Ejecutando este comando copiará los archivos de proyectos de configuración al directorio `~/.console/`. Sobreescribiendo los valores en estos archivos del directorio es como podrás cambiar el comportamiento de la Consola de Drupal.
 
 ```
 $ drupal init [--override]
 ```
 
### Cuáles archivos son copiados cuando el comando `init` es ejecutado.
```
 ~/.console/ 
 ├── aliases.yml 
 ├── chain
 │   ├── quick-start.yml
 │   └── sample.yml 
 ├── config.yml 
 ├── console.rc 
 ├── drupal.fish 
 └── sites 
     └── sample.yml 
```