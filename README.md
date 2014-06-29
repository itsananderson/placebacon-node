placebacon
===========

Simple CLI node utility that downloads files from [placebacon.net](http://placebacon.net).

Installation
------------

Installing is quite simple

```
npm install -g placebacon 
```

Usage
-----

Placebacon is pretty easy to use.

```
placebacon [-d path/to/download/folder] width[/height] [...]
```

Here are some concrete usage examples

```bash
placebacon 200/100 # Download a 200x100 image
placebacon 100/300 200 # Download a 100x300 image and a 200x200 image
placebacon -d bacon 800/600 # Download a 800x600 image into the bacon folder
```

In order for the -d (a.k.a. --directory) flag to work, the folder must already exist.
Otherwise placebacon will just return an error.
