famfamfam-mini
===============


[![NPM version](https://img.shields.io/npm/v/famfamfam-mini.svg)](https://www.npmjs.org/package/famfamfam-mini)
[![Bower version](https://img.shields.io/bower/v/famfamfam-mini.svg)](http://bower.io/search/?q=famfamfam-mini)
[![Packagist version](https://img.shields.io/packagist/v/t1st3/famfamfam-mini.svg)](https://packagist.org/packages/t1st3/famfamfam-mini)



About
----------

The `Mini` icon pack, as available on [famfamfam website](http://www.famfamfam.com/lab/icons/mini/).

All credits for these icons go to their original author: mjames@gmail.com

The aim of this project is to make this icon pack available through various package managers, such as:

- [NPM](https://npmjs.org)
- [Bower](http://bower.io)
- [Packagist](https://packagist.org)


All icons are supplied in GIF format.


CSS spritesheets
----------

You can insert the icons directly into your HTML with a common IMG tag:

```
    <img alt="Refresh" src="dist/gif/action_refresh_blue.gif" width="16" height="11">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

All the positioning of the icons inside this alone image is made through CSS, which allows you to just add block-type tags with the proper class and get the same result:

```
    <div class="famfamfam-mini action_refresh_blue"></div>
```

Just remember to add the CSS stylesheet to the HEAD of your HTML page!




Original readme (from author of the icons)
----------

mini icons - famfamfam.com
Contact: mjames@gmail.com


```
“Mini” is a set of 144 GIF icons available for free use for any purpose.
```



About the rest (all this repository but the icons)
----------

All the content of this repository (excepted the icon pack) 
is licensed under the [MIT license](http://opensource.org/licenses/MIT).

Though, it is just composed a few trivial json files and a Readme.



Get the package
----------

**NPM**

Get it with:

```
npm install famfamfam-mini
```


**Bower**

Get it with:

```
bower install famfamfam-mini
```

**Composer / Packagist**

[famfamfam-mini on Packagist](https://packagist.org/packages/t1st3/famfamfam-mini)



Dev dependencies and build status
----------

[![Dependency Status](https://img.shields.io/david/dev/T1st3/famfamfam-mini.svg)](https://david-dm.org/t1st3/famfamfam-mini)
[![Build Status](https://img.shields.io/travis/T1st3/famfamfam-mini.svg)](https://travis-ci.org/T1st3/famfamfam-mini)



