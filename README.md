#md-server

Edit your file with your favourite editor and get the result in the browser when you save the file.

A constant markdown file parsing, watching and reload server.
It's super easy to use, it could reload your browser when you save the markdown file.
Any [issue](https://github.com/chemzqm/md-server/issues) is welcome!

#Features

* **live edit**, browser will autoreload when the markdown file changed
* **gfm enabled** <https://help.github.com/articles/github-flavored-markdown>
* **syntax highlight** using [color-marked](https://github.com/chemzqm/marked) the css style is the same as github

##Install

Your have to install [node.js](http://nodejs.org/download/) at first.

``` sh
$ npm install -g md-server
```

##Usage

``` sh
$ md-server READE.md
```
open your browser with url <http://localhost:9300/md>
