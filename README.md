#doxdox

A simple documentation generator that takes output from [dox](https://github.com/visionmedia/dox/) and builds a [Bootstrap](http://getbootstrap.com/) based documentation file.

##Installation

```bash
sudo pip install https://github.com/neogeek/doxdox/zipball/master
```

##Usage

```bash
usage: doxdox.py [-h] [-t TITLE] [-d DESCRIPTION] [-l {bootstrap}] [dir]

HTML generator for Dox Documentation

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
```

##Examples

- Facade.js Documentation <http://docs.facadejs.com>