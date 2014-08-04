#doxdox

[![version](https://pypip.in/v/doxdox/badge.svg)](https://pypi.python.org/pypi/doxdox/) [![downloads](https://pypip.in/d/doxdox/badge.svg)](https://pypi.python.org/pypi/doxdox/)

A simple documentation generator that takes output from [dox](https://github.com/visionmedia/dox/) and builds a [Bootstrap](http://getbootstrap.com/) based documentation file.

##Installation

```bash
$ pip install --pre doxdox
```

##Usage

```bash
usage: doxdox.py [-h] [-t TITLE] [-d DESCRIPTION] [-l {bootstrap}]
                 [--header HEADER] [--footer FOOTER]
                 [dir]

HTML generator for Dox Documentation (0.3.1alpha)

positional arguments:
  dir                   Directory to search for .json files in.

optional arguments:
  -h, --help            show this help message and exit
  -t TITLE, --title TITLE
                        The project title. Default is "Untitled Project".
  -d DESCRIPTION, --description DESCRIPTION
                        The project description. Default is blank.
  -l {bootstrap}, --layout {bootstrap}
                        The template to render the documentation with. Default
                        is bootstrap.
  --header HEADER       HTML include file (positioned above the content).
  --footer FOOTER       HTML include file (positioned below the content).
```

##Examples

- Facade.js Documentation <http://docs.facadejs.com>

![screenshot](http://f.cl.ly/items/2s3Z1u471I2k0U0a143a/doxdox-screenshot.png)
