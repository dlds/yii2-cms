yii2-cms
=============

[![Latest Stable Version](https://poser.pugx.org/dlds/yii2-cms/v/stable)](https://packagist.org/packages/dlds/yii2-cms)
[![License](https://poser.pugx.org/dlds/yii2-cms/license)](https://packagist.org/packages/dlds/yii2-cms)
[![Total Downloads](https://poser.pugx.org/dlds/yii2-cms/downloads)](https://packagist.org/packages/dlds/yii2-cms)
[![Monthly Downloads](https://poser.pugx.org/dlds/yii2-cms/d/monthly)](https://packagist.org/packages/dlds/yii2-cms)
[![Daily Downloads](https://poser.pugx.org/dlds/yii2-cms/d/daily)](https://packagist.org/packages/dlds/yii2-cms)

The **yii2-cms**  module easy CMS system supports basic features of each simple blog. The main features of this module are:

- Posibility to run multiple blogs on single Yii2 installation
- Creating blog categories and enabling them in specific blog
- Creating blog articles and enabling them in specific blog
- Editing meta values like meta title, meta description for each article, category, blog
- Multilangual support for blog categories, articles, metas, images titles, blog itself
- Automatic publishing of each article on specified date time
- Supports friendly URLs and easy managing og url slugs for each article, category, blog
- Storing history URL slugs to keep old URLs working (using redirect 301)
- Manual sorting of articles
- Tree nesting of categories

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

> Note: Check the [composer.json](https://github.com/dlds/yii2-cms/blob/master/composer.json) for this extension's requirements and dependencies. 


Either run

```
$ php composer.phar require dlds/yii2-cms "@stable"
```

or add

```
"dlds/yii2-cms": "@stable"
```

to the ```require``` section of your `composer.json` file.

## License

**yii2-cms** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.
