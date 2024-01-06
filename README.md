# Stacey 3.1.0 (Unofficial PHP 8 Retrofit)

## Overview

Responsive portfolio style template for Stacey 3 updated for compatibility with PHP 8.2.
Modified from the default template for myself and shared here for public usage. 

Patched errors related to PHP 8: 

- in the base app, 

- in the included Twig 1.x library, 

- in the included SLIR library and 

- updated the Markdown Extra parser library to the last version.

All the libraries remain close to the original versions and aren't composer managed to keep it simple, hence retrofit rather than update. 

Stacey takes content from `.yml` files, image files and implied directory structure and generates a website.
It is a no-database, dynamic website generator.

If you look in the `/content` and `/templates` folders, you should get the general idea of how it all works.

## Installation

Copy to server, `chmod 777 app/_cache`.

If you want clean urls, `mv htaccess .htaccess`

## Templates

Stacey uses the [Twig templating language](http://twig.sensiolabs.org/).

There are an additional two sets of templates which can be found at:
<http://github.com/kolber/stacey-template2> &
<http://github.com/kolber/stacey-template3>

## Read More

See <http://staceyapp.com> for more detailed usage information.

## Copyright/License

Copyright (c) 2009 Anthony Kolber. See `LICENSE` for details.
Except [PHP Markdown Extra](http://michelf.com/projects/php-markdown/extra/) which is (c) Michel Fortin (see `/app/parsers/markdown-parser.inc.php` for details) and
[jsmin.php](https://github.com/rgrove/jsmin-php/) which is (c) Ryan Grove (see `app/parsers/json-minifier.inc.php` for details).