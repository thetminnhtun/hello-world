# Hello World

This is my first composer testing project 

### Installation
___
#### With Composer

```
$ composer require thetminnhtun/hello-world
```

```php
<?php 
require_once __DIR__ . '/vendor/autoload.php'; // Autoload files using Composer autoload
use HelloWorld\SayHello;
echo SayHello::world();
```


from [tutoiral](https://blog.jgrossi.com/2013/creating-your-first-composer-packagist-package)

