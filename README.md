tiny-lr-it
===
> Run tiny-lr and watch target directories on the fly

Quick and easy way to start a [LiveReload](http://livereload.com/) server and define a list of directories to "watch".

_Uses the awesome [tiny-lr](https://github.com/mklabs/tiny-lr) and [node-watch](https://github.com/yuanchuan/node-watch) modules to start a live-reload server and watch target directories._

installation
---
```
npm install -g tiny-lr-it
```

usage
---
Provide a comma-delited list of directories to watch. *Note: it will be recursive.*

```
tiny-lr-it .
```

```
  usage: tiny-lr-it [dirs]

  Starts a tiny-livereload server and file watcher on provided target dirs.

  options:
    -h                  Display help menu
    -p                  Desired port to start server on localhost
```

acknowledgements
---
This could not be possible without these awesome nodejs modules:

* [tiny-lr](https://github.com/mklabs/tiny-lr)
* [node-watch](https://github.com/yuanchuan/node-watch)