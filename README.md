famfamfam-mini
===============


[![NPM version](https://img.shields.io/npm/v/famfamfam-mini.svg)](https://www.npmjs.org/package/famfamfam-mini)
[![Bower version](https://img.shields.io/bower/v/famfamfam-mini.svg)](http://bower.io/search/?q=famfamfam-mini)
[![Packagist version](https://img.shields.io/packagist/v/t1st3/famfamfam-mini.svg)](https://packagist.org/packages/t1st3/famfamfam-mini)


[![Dependency Status](https://img.shields.io/david/dev/T1st3/famfamfam-mini.svg)](https://david-dm.org/t1st3/famfamfam-mini)
[![Build Status](https://img.shields.io/travis/T1st3/famfamfam-mini.svg)](https://travis-ci.org/T1st3/famfamfam-mini)




About
----------

The `Mini` icon pack, as available on [famfamfam website](http://www.famfamfam.com/lab/icons/mini/).

All credits for these icons go to their original author: Mark James (mjames@gmail.com)

The aim of this project is to make this icon pack available through various package managers, such as:

- [NPM](https://npmjs.org)
- [Bower](http://bower.io)
- [Packagist](https://packagist.org)


All icons are supplied in GIF format.


CSS spritesheets
----------

You can insert the icons directly into your HTML with a common IMG tag:

```
    <img alt="Refresh" src="dist/gif/action_refresh_blue.gif" width="16" height="16">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

This is what it actually looks:

![Spritesheet](https://raw.githubusercontent.com/T1st3/famfamfam-mini/master/dist/sprite/famfamfam-mini.png)


All the positioning of the icons inside this alone image is made through CSS, which allows you to just add block-type tags with the proper class and get the same result:

```
    <div class="famfamfam-mini action_refresh_blue"></div>
```

Just remember to add the CSS stylesheet to the HEAD of your HTML page!



Get the package with NPM
----------

Just run the following on the CLI (provided your CLI is directed to your work directory)

```
npm install famfamfam-mini
```



Get the package with Bower
----------

Just run the following on the CLI (provided your CLI is directed to your work directory)

```
bower install famfamfam-mini
```


Get the package with Packagist
----------

[famfamfam-mini on Packagist](https://packagist.org/packages/t1st3/famfamfam-mini)







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



