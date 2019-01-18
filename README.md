yii2-bank-card-info
===================
yii2-bank-card-info

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist wdteam/yii2-bank-card-info "*"
```

or add

```
"wdteam/yii2-bank-card-info": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \wdteam\bankCard\BankCardInfo::getBankList(); ?>```