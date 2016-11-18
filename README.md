
yii2命令行中使用migration备份和还原数据库
===========================
yii2命令行中使用migration备份和还原数据库


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist e282486518/yii2-console-migration "*"
```

or add

```
"e282486518/yii2-console-migration": "*"
```

to the require section of your `composer.json` file.


Usage
-----

在```console\config\main.php```中添加  :

```php
    'controllerMap' => [
        'migrates' => [
            'class' => 'e282486518\migration\ConsoleController',
        ],
    ],
```