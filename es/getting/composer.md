# Instala Drupal Console Usando Composer
Puedes instalar este proyecto usando composer.

## Instalando Drupal Console globalmente usando composer:
```
$ composer global require drupal/console:@stable
```

## Agregar el directorio binario a la ruta de clases:
```
$ echo "PATH=$PATH:~/.composer/vendor/bin" >> ~/.bash_profile
```

## Ahora executa console usando:
```
$ drupal generate:module
```
