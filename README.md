Шаблон smarty boostrap
===================================

Информация
-------------------

Это просто нетронутый шаблон купленный тут http://wrapbootstrap.com/preview/WB008R559
И оформленный для работы с yii2 проектами

Установка
------------

1) Добавить в `composer.json` файл проекта.

```
"skeeks/yii2-template-cube-admin": "*"
```


Пример использования
------------

Решение оформлено для работы с yii2 проектами. Для использования в проекте создается собственный AssetBoundle который наследуется от родительского skeeks\template\smarty\SmartyAsset и набираются нужные файлы css и js.
Ну а html разметка за разработчиком.

```php

<?php
namespace frontend\assets;

use skeeks\template\cube\CubeAsset;

/**
 * Class CubeAsset
 * @package frontend\assets
 */
class SmartyThemeAsset extends CubeAsset
{
    public $css = [
        'https://fonts.googleapis.com/css?family=Open+Sans:300,400%7CRaleway:300,400,500,600,700%7CLato:300,400,400italic,600,700',
        'css/essentials.css',
        'css/layout.css',
        'css/header-1.css',
        'css/color_scheme/green.css',
    ];

    public $js = [
        //'js/scripts.js',
    ];
}


```

> [![skeeks!](https://gravatar.com/userimage/74431132/13d04d83218593564422770b616e5622.jpg)](http://www.skeeks.com)
<i>Быстро, просто, эффективно</i>
[cms.skeeks.com](http://cms.skeeks.com)
