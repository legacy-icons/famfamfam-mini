famfamfam-mini
===============


[![NPM version](https://img.shields.io/npm/v/famfamfam-mini.svg)](https://www.npmjs.org/package/famfamfam-mini)
[![Bower version](https://img.shields.io/bower/v/famfamfam-mini.svg)](http://bower.io/search/?q=famfamfam-mini)
[![Packagist version](https://img.shields.io/packagist/v/t1st3/famfamfam-mini.svg)](https://packagist.org/packages/t1st3/famfamfam-mini)
[![Nuget version](https://img.shields.io/nuget/v/famfamfam-mini.svg)](https://www.nuget.org/packages/famfamfam-mini/)

[![Dependency Status](https://img.shields.io/david/dev/t1st3/famfamfam-mini.svg)](https://david-dm.org/t1st3/famfamfam-mini)
[![Build Status](https://img.shields.io/travis/t1st3/famfamfam-mini.svg)](https://travis-ci.org/t1st3/famfamfam-mini)




About
----------

The `Mini` icon pack, as available on [famfamfam website](http://www.famfamfam.com/lab/icons/mini/).

All credits for these icons go to their original author: Mark James (mjames@gmail.com)

The aim of this project is to make this icon pack available through various package managers, such as:

- [NPM](https://npmjs.org)
- [Bower](http://bower.io)
- [Packagist](https://packagist.org)
- [NuGet](https://www.nuget.org)


All icons are supplied in GIF format.


CSS spritesheets
----------

You can insert the icons directly into your HTML with a common IMG tag:

```
    <img alt="Refresh" src="dist/gif/action_refresh_blue.gif" width="16" height="16">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

This is what it actually looks:

![Spritesheet](https://raw.githubusercontent.com/t1st3/famfamfam-mini/master/dist/sprite/famfamfam-mini.png)


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


Get the package with Composer / Packagist
----------

Just run the following on the CLI (provided your CLI is directed to your work directory)

```
composer require t1st3/famfamfam-mini
```


Get the package with NuGet
----------

Just run the following on the CLI (provided your CLI is directed to your work directory)

```
Install-Package famfamfam-mini
```




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




Build (the whole project or your custom project)
----------


We use [Gulp](http://gulpjs.com/) to build the project, so if you want to re-build or customize this project, you'll need Gulp.

After gulp is installed, and your CLI is pointed to your work directory, first install the dependencies:

```
     npm install
```


then, you can run the `gulp build` task to build the project:


```
     gulp build
```




**What the build task does?**

First, it copies GIF files from the `src` folder, and pastes them to the `dist` folder.

Then it creates a spritesheet from the GIF images located in the `src` folder, and thus creates the `sprite` folder in `dist`.

If, for example you just want `action_stop` and `page_right` icons in a spritesheet, you just have to fork this project, point your CLI to the working directory, 
empty the `src` directory, except `action_stop` and `page_right` icons in GIF format, and then run the `gulp build` task.

You'll get the proper spritesheet and copies of the icons directly in the `dist` folder.
