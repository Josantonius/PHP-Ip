# PHP Ip library

[![Latest Stable Version](https://poser.pugx.org/josantonius/ip/v/stable)](https://packagist.org/packages/josantonius/ip) [![Total Downloads](https://poser.pugx.org/josantonius/ip/downloads)](https://packagist.org/packages/josantonius/ip) [![Latest Unstable Version](https://poser.pugx.org/josantonius/ip/v/unstable)](https://packagist.org/packages/josantonius/ip) [![License](https://poser.pugx.org/josantonius/ip/license)](https://packagist.org/packages/josantonius/ip) [![Travis](https://travis-ci.org/Josantonius/PHP-Ip.svg)](https://travis-ci.org/Josantonius/PHP-Ip)

[English version](README.md)

Biblioteca PHP para obtener la IP del usuario.

---

- [Instalación](#instalación)
- [Requisitos](#requisitos)
- [Cómo empezar y ejemplos](#cómo-empezar-y-ejemplos)
- [Métodos disponibles](#métodos-disponibles)
- [Uso](#uso)
- [Tests](#tests)
- [Contribuir](#contribuir)
- [Repositorio](#repositorio)
- [Licencia](#licencia)
- [Copyright](#copyright)

---

### Instalación 

La mejor forma de instalar esta extensión es a través de [composer](http://getcomposer.org/download/).

Para instalar PHP Ip library, simplemente escribe:

    $ composer require Josantonius/Ip

El comando anterior sólo instalará los archivos necesarios, si prefieres descargar todo el código fuente (incluyendo tests, directorio vendor, excepciones no utilizadas, documentos...) puedes utilizar:

    $ composer require Josantonius/Ip --prefer-source

También puedes clonar el repositorio completo con Git:

	$ git clone https://github.com/Josantonius/PHP-Ip.git

### Requisitos

Esta biblioteca es soportada por versiones de PHP 5.6 o superiores y es compatible con versiones de HHVM 3.0 o superiores.

### Cómo empezar y ejemplos

Para utilizar esta biblioteca, simplemente:

```php
require __DIR__ . '/vendor/autoload.php';

use Josantonius\Ip\Ip;
```
### Métodos disponibles

Métodos disponibles en esta biblioteca:

```php
Ip::get();
```
### Uso

Ejemplo de uso para esta biblioteca:

```php
<?php
require __DIR__ . '/vendor/autoload.php';

use Josantonius\Ip\Ip;

print_r(Ip::get()); # 66.249.76.29
```

### Tests 

Para ejecutar las [pruebas](tests/Ip/test) simplemente:

    $ git clone https://github.com/Josantonius/PHP-Ip.git
    
    $ cd PHP-Ip

    $ phpunit

### Contribuir
1. Comprobar si hay incidencias abiertas o abrir una nueva para iniciar una discusión en torno a un fallo o función.
1. Bifurca la rama del repositorio en GitHub para iniciar la operación de ajuste.
1. Escribe una o más pruebas para la nueva característica o expón el error.
1. Haz cambios en el código para implementar la característica o reparar el fallo.
1. Envía pull request para fusionar los cambios y que sean publicados.

Esto está pensado para proyectos grandes y de larga duración.

### Repositorio

Los archivos de este repositorio se crearon y subieron automáticamente con [Reposgit Creator](https://github.com/Josantonius/BASH-Reposgit).

### Licencia

Este proyecto está licenciado bajo **licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.

### Copyright

2017 Josantonius, [josantonius.com](https://josantonius.com/)

Si te ha resultado útil, házmelo saber :wink:

Puedes contactarme en [Twitter](https://twitter.com/Josantonius) o a través de mi [correo electrónico](mailto:hello@josantonius.com).