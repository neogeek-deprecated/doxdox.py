#doxdox

A simple documentation generator that takes output from [dox](https://github.com/visionmedia/dox/) and builds a [Bootstrap](http://getbootstrap.com/) based documentation file.

##Installation 

```bash
sudo pip install https://github.com/neogeek/doxdox/zipball/master
```

##Usage

Run the following command in the same directory as your dox files.

```bash
doxdox.py -t "Title of project" -d "Short description of project." > docs.html
```