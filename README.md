# yii2-schema-breadcrumbs

Use data structured breadcrumbs from [schema.org](https://schema.org/BreadcrumbList) on yii2 projects.

## How to install

```
$ composer require orige/yii2-schema-breadcrumbs
```

## How to use
```php
use SchemaBreadcrumbs\SchemaBreadcrumbs as Breadcrumbs

Breadcrumbs::widget([
    'links' => $links,
]);
```
You don't have to specify any data structure property inside the `Breadcrumbs` object. It will work automatically.

## Documentation

This widget should be work as good as the yii2 official. So, I won't copy/paste
their documentation.

To see how you can work with breadcrumbs in a yii2 project,
[click here](http://www.yiiframework.com/doc-2.0/yii-widgets-breadcrumbs.html)


## TODO
- tests
- comment the code
- improve documentation with examples
