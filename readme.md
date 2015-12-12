yo jekyllrb [that works]
===

A bare `yo jekyllrb` generated app, patched to work in my current enviroment.

Precompiled with 

* Sass 
* Autoprefixer 
* Coffeescript 
* default directory structure (css/js/img/fonts/_scss/_src) 
* HTML5 ★ Boilerplate incl. css + js + icon files, analytics and documentation
* grunt-build-control
* Post permalink style: pretty
* Markdown library: kramdown


**Fixes**:

* `Gemfile`: Set each gem on its own line + update `jekyll` to version `2.5.3`.
* `package.json`: Update browsersync: `$ sudo npm install grunt-browser-sync --save-dev`
* `Gruntfile.js`: Replace double quotes with single to make build pass
* `.editorconfig`: Set default indentation to 4, and add 2 for coffee


## Usage

 Clone this repo
 
    $ git clone https://github.com/Djarnis/yo-jekyllrb

Rename to whatever your project's called ...
    
    $ mv yo-jekyllrb __my_awesome_project__

`cd` into your awesome project

    $ cd __my_awesome_project__

Install dependencies

    $ sudo npm install

Install frontend dependencies

    $ bower install

Run developer server

    $ grunt serve


