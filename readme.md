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




## Installation log

I'll keep this around to see what I changed and why :)

### $ yo jekyllrb

```
    $ yo jekyllrb

         _-----_
        |       |    .------------------------------------------.
        |--(o)--|    | Update available: 1.5.0 (current: 1.4.6) |
       `---------´   |     Run npm install -g yo to update.     |
        ( _´U`_ )    '------------------------------------------'
        /___A___\    
         |  ~  |     
       __'.___.'__   
     ´   `  |° ´ Y ` 

    undefined
    This generator will scaffold and wire a Jekyll site. Yo, Jekyllrb!

    Tell us a little about yourself. ☛
    ? Name: Jeppe Bårris
    ? Email: jeppe@barris.dk

    Wire tools and preprocessors. ☛
    ? CSS preprocessor: Sass
    ? Use Autoprefixer? Yes
    ? Javascript preprocessor: Coffeescript

    Set up some directories. ☛
    See note about nested directories in the README.
    ? CSS directory: css
    ? Javascript directory: js
    ? Image directory: img
    ? Webfont directory: fonts
    ? CSS preprocessor directory: _scss
    ? Javascript preprocessor directory: _src

    Choose a template. ☛
    ? Site template: HTML5 ★ Boilerplate
    ? Add H5★BP CSS files? Yes
    ? Add H5★BP javascript files? Yes
    ? Add H5★BP favorite and touch icons? Yes
    ? Add H5★BP documentation? Yes
    ? Include Google Analytics? Yes

    Choose deployment options. ☛
    ? Use grunt-build-control for deployment? Yes
    ? Remote to deploy to: ../
    ? Branch to deploy to: gh-pages

    And finally, configure Jekyll. ☛
    You can change all of these options in _config.yml.
    ? Site description: 
    ? Post permalink style: pretty
    ? Markdown library: kramdown
    ? Use the Pygments code highlighting library? No
    ? Number of posts to show on the home page: all
    New jekyll site installed in /Users/jeppe/apps/mdd/mdd_yo_jekyll/.jekyll. 
       create bower.json
       create package.json
       create .gitignore
       create .gitattributes
       create Gruntfile.js
       create .bowerrc
       create Gemfile
       create .jshintrc
       create .csslintrc
       create .editorconfig
       create _config.build.yml
       create _config.yml
       create app/_posts/2015-12-08-welcome-to-jekyll.md
       create app/_posts/2015-12-08-yo-jekyllrb.md
       create app/index.html
       create app/_layouts/post.html
       create app/_includes/scripts.html
       create app/_layouts/default.html
       create app/_includes/googleanalytics.html
       create app/.htaccess
       create app/404.html
       create app/crossdomain.xml
       create app/_h5bp-docs/LICENSE.md
       create app/robots.txt
       create app/humans.txt
       create app/css/main.css
       create app/js/main.js
       create app/js/plugins.js
       create app/apple-touch-icon-precomposed.png
       create app/favicon.ico
       create app/_h5bp-docs/code-docs/crossdomain.md
       create app/_h5bp-docs/code-docs/css.md
       create app/_h5bp-docs/code-docs/extend.md
       create app/_h5bp-docs/code-docs/faq.md
       create app/_h5bp-docs/code-docs/html.md
       create app/_h5bp-docs/code-docs/js.md
       create app/_h5bp-docs/code-docs/misc.md
       create app/_h5bp-docs/code-docs/TOC.md
       create app/_h5bp-docs/code-docs/usage.md
       create app/_h5bp-docs/CHANGELOG.md
       create app/_h5bp-docs/CONTRIBUTING.md
       create app/_h5bp-docs/README.md
       create app/_scss/readme.md
       create app/_src/readme.md


    I'm all done. Running npm install & bower install for you to install the required dependencies. If this fails, try running the command yourself.
```


### $ sudo npm install [SUCCESS]

```
    $ sudo npm install
    Password:
    npm WARN peerDependencies The peer dependency coffeelint@^1 included from grunt-coffeelint will no
    npm WARN peerDependencies longer be automatically installed to fulfill the peerDependency 
    npm WARN peerDependencies in npm 3+. Your application will need to depend on it explicitly.
    npm WARN deprecated find-file@1.0.1: Use the globby package instead
     
    > spawn-sync@1.0.14 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-optipng/node_modules/optipng-bin/node_modules/bin-wrapper/node_modules/bin-check/node_modules/spawn-sync
    > node postinstall

     
    > spawn-sync@1.0.14 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-gifsicle/node_modules/gifsicle/node_modules/bin-wrapper/node_modules/bin-check/node_modules/spawn-sync
    > node postinstall

     
    > spawn-sync@1.0.14 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-jpegtran/node_modules/jpegtran-bin/node_modules/bin-wrapper/node_modules/bin-check/node_modules/spawn-sync
    > node postinstall

     
    > spawn-sync@1.0.14 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-pngquant/node_modules/pngquant-bin/node_modules/bin-wrapper/node_modules/bin-check/node_modules/spawn-sync
    > node postinstall

     
    > ws@0.4.31 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/socket.io/node_modules/engine.io/node_modules/ws
    > (node-gyp rebuild 2> builderror.log) || (exit 0)

      CXX(target) Release/obj.target/bufferutil/src/bufferutil.o

    > jpegtran-bin@1.0.2 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-jpegtran/node_modules/jpegtran-bin
    > node lib/install.js

         fetch : https://raw.github.com/imagemin/jpegtran-bin/v1.0.2/vendor/osx/jpegtran
      progress : [====================] 100% 0.0s

    ✔ pre-build test passed successfully!

    > pngquant-bin@1.0.1 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-pngquant/node_modules/pngquant-bin
    > node lib/install.js

         fetch : https://raw.github.com/imagemin/pngquant-bin/v1.0.1/vendor/osx/pngquant
      progress : [====================] 100% 0.0s

    ✔ pre-build test passed successfully!

    > gifsicle@1.0.3 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-gifsicle/node_modules/gifsicle
    > node lib/install.js

         fetch : https://raw.github.com/imagemin/gifsicle-bin/v1.0.3/vendor/osx/gifsicle
      progress : [====================] 100% 0.0s

    ✔ pre-build test passed successfully!

    > optipng-bin@1.0.1 postinstall /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-contrib-imagemin/node_modules/imagemin/node_modules/imagemin-optipng/node_modules/optipng-bin
    > node lib/install.js

         fetch : https://raw.github.com/imagemin/optipng-bin/v1.0.1/vendor/osx/optipng
      progress : [====================] 100% 0.0s

    ✔ pre-build test passed successfully!

    > ws@0.4.31 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/socket.io/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/ws
    > (node-gyp rebuild 2> builderror.log) || (exit 0)

      CXX(target) Release/obj.target/bufferutil/src/bufferutil.o
    grunt-contrib-copy@0.5.0 node_modules/grunt-contrib-copy

    grunt-contrib-clean@0.6.0 node_modules/grunt-contrib-clean
    └── rimraf@2.2.8

    grunt-filerev@0.2.1 node_modules/grunt-filerev
    ├── each-async@0.1.3
    └── chalk@0.4.0 (ansi-styles@1.0.0, has-color@0.1.7, strip-ansi@0.1.1)

    grunt-concurrent@0.5.0 node_modules/grunt-concurrent
    ├── async@0.2.10
    └── pad-stdio@0.1.1 (lpad@0.2.1)

    time-grunt@0.4.0 node_modules/time-grunt
    ├── date-time@0.1.1
    ├── figures@1.4.0
    ├── text-table@0.2.0
    ├── hooker@0.2.3
    ├── pretty-ms@0.2.2 (parse-ms@0.1.2)
    └── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, has-ansi@0.1.0, strip-ansi@0.3.0)

    jshint-stylish@0.4.0 node_modules/jshint-stylish
    ├── text-table@0.2.0
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, has-ansi@0.1.0, strip-ansi@0.3.0)
    └── log-symbols@1.0.2 (chalk@1.1.1)

    grunt-contrib-sass@0.8.1 node_modules/grunt-contrib-sass
    ├── dargs@2.1.0
    ├── win-spawn@2.0.0
    ├── async@0.9.2
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, strip-ansi@0.3.0, has-ansi@0.1.0)
    └── which@1.2.0 (is-absolute@0.1.7)

    grunt-build-control@0.1.8 node_modules/grunt-build-control
    └── shelljs@0.2.6

    grunt-jekyll@0.4.3 node_modules/grunt-jekyll
    └── tmp@0.0.28 (os-tmpdir@1.0.1)

    grunt-contrib-concat@0.5.1 node_modules/grunt-contrib-concat
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, has-ansi@0.1.0, strip-ansi@0.3.0)
    └── source-map@0.3.0 (amdefine@1.0.0)

    grunt-contrib-csslint@0.4.0 node_modules/grunt-contrib-csslint
    ├── strip-json-comments@1.0.4
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, strip-ansi@0.3.0, has-ansi@0.1.0)
    ├── csslint@0.10.0 (parserlib@0.2.5)
    └── lodash@2.4.2

    grunt-contrib-coffee@0.11.1 node_modules/grunt-contrib-coffee
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, has-ansi@0.1.0, strip-ansi@0.3.0)
    ├── coffee-script@1.7.1 (mkdirp@0.3.5)
    └── lodash@2.4.2

    grunt-usemin@2.4.0 node_modules/grunt-usemin
    ├── debug@1.0.4 (ms@0.6.2)
    └── lodash@2.4.2

    grunt-contrib-watch@0.6.1 node_modules/grunt-contrib-watch
    ├── async@0.2.10
    ├── tiny-lr-fork@0.0.5 (debug@0.7.4, faye-websocket@0.4.4, noptify@0.0.3, qs@0.5.6)
    ├── gaze@0.5.2 (globule@0.1.0)
    └── lodash@2.4.2

    load-grunt-tasks@0.6.0 node_modules/load-grunt-tasks
    ├── multimatch@0.3.0 (array-differ@0.1.0, array-union@0.1.0, minimatch@0.3.0)
    └── findup-sync@0.1.3 (glob@3.2.11, lodash@2.4.2)

    grunt-contrib-htmlmin@0.3.0 node_modules/grunt-contrib-htmlmin
    ├── pretty-bytes@0.1.2
    ├── chalk@0.4.0 (ansi-styles@1.0.0, has-color@0.1.7, strip-ansi@0.1.1)
    └── html-minifier@0.6.9 (relateurl@0.2.6, change-case@2.1.6, clean-css@2.2.23, cli@0.6.6, uglify-js@2.4.24)

    grunt@0.4.5 node_modules/grunt
    ├── which@1.0.9
    ├── dateformat@1.0.2-1.2.3
    ├── eventemitter2@0.4.14
    ├── getobject@0.1.0
    ├── rimraf@2.2.8
    ├── colors@0.6.2
    ├── async@0.1.22
    ├── grunt-legacy-util@0.2.0
    ├── hooker@0.2.3
    ├── exit@0.1.2
    ├── nopt@1.0.10 (abbrev@1.0.7)
    ├── minimatch@0.2.14 (sigmund@1.0.1, lru-cache@2.7.3)
    ├── glob@3.1.21 (inherits@1.0.2, graceful-fs@1.2.3)
    ├── lodash@0.9.2
    ├── coffee-script@1.3.3
    ├── underscore.string@2.2.1
    ├── iconv-lite@0.2.11
    ├── findup-sync@0.1.3 (glob@3.2.11, lodash@2.4.2)
    ├── grunt-legacy-log@0.1.2 (grunt-legacy-log-utils@0.1.1, underscore.string@2.3.3, lodash@2.4.2)
    └── js-yaml@2.0.5 (argparse@0.1.16, esprima@1.0.4)

    grunt-contrib-cssmin@0.10.0 node_modules/grunt-contrib-cssmin
    ├── chalk@0.4.0 (ansi-styles@1.0.0, has-color@0.1.7, strip-ansi@0.1.1)
    ├── clean-css@2.2.23 (commander@2.2.0)
    └── maxmin@0.2.2 (figures@1.4.0, pretty-bytes@0.1.2, chalk@0.5.1, gzip-size@0.2.0)

    grunt-contrib-uglify@0.5.1 node_modules/grunt-contrib-uglify
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, strip-ansi@0.3.0, has-ansi@0.1.0)
    ├── lodash@2.4.2
    ├── maxmin@0.2.2 (figures@1.4.0, pretty-bytes@0.1.2, gzip-size@0.2.0)
    └── uglify-js@2.6.1 (uglify-to-browserify@1.0.2, async@0.2.10, yargs@3.10.0, source-map@0.5.3)

    grunt-svgmin@0.4.0 node_modules/grunt-svgmin
    ├── each-async@0.1.3
    ├── pretty-bytes@0.1.2
    ├── chalk@0.4.0 (has-color@0.1.7, ansi-styles@1.0.0, strip-ansi@0.1.1)
    └── svgo@0.4.5 (colors@0.6.2, whet.extend@0.9.9, coa@0.4.1, sax@0.6.1, js-yaml@2.1.3)

    coffeelint@1.14.2 node_modules/coffeelint
    ├── strip-json-comments@1.0.4
    ├── ignore@2.2.19
    ├── resolve@0.6.3
    ├── optimist@0.6.1 (wordwrap@0.0.3, minimist@0.0.10)
    ├── coffee-script@1.10.0
    └── glob@4.5.3 (inherits@2.0.1, inflight@1.0.4, once@1.3.3, minimatch@2.0.10)

    grunt-coffeelint@0.0.13 node_modules/grunt-coffeelint
    └── coffeelint-stylish@0.1.2 (text-table@0.2.0, chalk@1.1.1)

    grunt-contrib-jshint@0.10.0 node_modules/grunt-contrib-jshint
    ├── hooker@0.2.3
    └── jshint@2.5.11 (strip-json-comments@1.0.4, underscore@1.6.0, exit@0.1.2, shelljs@0.3.0, console-browserify@1.1.0, minimatch@1.0.0, cli@0.6.6, htmlparser2@3.8.3)

    grunt-autoprefixer@1.0.1 node_modules/grunt-autoprefixer
    ├── diff@1.0.8
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, has-ansi@0.1.0, strip-ansi@0.3.0)
    └── autoprefixer-core@3.1.2 (postcss@2.2.6, caniuse-db@1.0.30000375)

    grunt-contrib-imagemin@0.8.1 node_modules/grunt-contrib-imagemin
    ├── async@0.9.2
    ├── chalk@0.5.1 (ansi-styles@1.1.0, escape-string-regexp@1.0.3, supports-color@0.2.0, strip-ansi@0.3.0, has-ansi@0.1.0)
    ├── pretty-bytes@1.0.4 (get-stdin@4.0.1, meow@3.6.0)
    └── imagemin@1.0.5 (get-stdin@3.0.2, stat-mode@0.2.1, ware@0.3.0, nopt@3.0.6, tempfile@1.1.1, fs-extra@0.11.1, imagemin-svgo@1.0.2, imagemin-jpegtran@1.0.0, imagemin-pngquant@1.0.2, imagemin-gifsicle@1.0.0, imagemin-optipng@1.0.0)

    grunt-browser-sync@1.3.7 node_modules/grunt-browser-sync
    └── browser-sync@1.3.7 (emitter-steward@0.0.1, foxy@0.2.1, commander@2.3.0, opn@1.0.2, minimist@1.2.0, cl-strings@0.0.5, ua-parser-js@0.7.9, connect@3.1.1, browser-sync-client@0.3.1, serve-static@1.10.0, opt-merger@0.1.3, portscanner-plus@0.1.0, http-proxy@1.3.0, serve-index@1.7.2, glob-watcher@0.0.6, lodash@2.4.2, dev-ip@0.1.7, localtunnel@1.8.0, resp-modifier@0.1.2, socket.io@1.0.6)
```


### $ bower install [SUCCESS]

```
    $ bower install
    bower cached        git://github.com/necolas/normalize.css.git#3.0.3
    bower validate      3.0.3 against git://github.com/necolas/normalize.css.git#~3.0.1
    bower cached        git://github.com/jquery/jquery.git#1.11.3
    bower validate      1.11.3 against git://github.com/jquery/jquery.git#~1.11.1
    bower cached        git://github.com/Modernizr/Modernizr.git#2.8.3
    bower validate      2.8.3 against git://github.com/Modernizr/Modernizr.git#~2.8.3
    bower install       normalize-css#3.0.3
    bower install       modernizr#2.8.3
    bower install       jquery#1.11.3

    normalize-css#3.0.3 app/_bower_components/normalize-css

    modernizr#2.8.3 app/_bower_components/modernizr

    jquery#1.11.3 app/_bower_components/jquery
```

### $ grunt serve [FAILS][JEKYLL_VERSION_ERROR]

```
    $ grunt serve
    Running "serve" task

    Running "clean:server" (clean) task
    >> 0 paths cleaned.

    Running "concurrent:server" (concurrent) task
        
        Running "coffee:dist" (coffee) task
        >> 0 files created.
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:13:44 UTC)
        loading tasks  3.5s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.5s
            
        Running "copy:stageCss" (copy) task
        Copied 1 files
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:13:45 UTC)
        loading tasks  3.4s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.4s
            
        Running "sass:server" (sass) task
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:13:44 UTC)
        loading tasks  3.5s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.5s
            Warning: Running "jekyll:server" (jekyll) task
        >> Error: Command failed: /bin/sh -c jekyll -v
        >> /usr/local/rvm/gems/ruby-1.9.2-p320@global/gems/bundler-1.3.5/lib/bundler/dsl.rb:33:in `rescue in eval_gemfile': Gemfile syntax error: (Bundler::GemfileError)
        >> gem 'jekyll', '~> 2.3.0'gem 'kramdown'gem 'sass', '~> 3.4.3'
        >>                            ^
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320@global/gems/bundler-1.3.5/lib/bundler/dsl.rb:29:in `eval_gemfile'
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320@global/gems/bundler-1.3.5/lib/bundler/dsl.rb:9:in `evaluate'
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320@global/gems/bundler-1.3.5/lib/bundler/definition.rb:19:in `build'
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320@global/gems/bundler-1.3.5/lib/bundler.rb:148:in `definition'
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320@global/gems/bundler-1.3.5/lib/bundler.rb:116:in `setup'
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320/gems/jekyll-2.5.3/lib/jekyll/plugin_manager.rb:37:in `require_from_bundler'
        >>  from /usr/local/rvm/gems/ruby-1.9.2-p320/gems/jekyll-2.5.3/bin/jekyll:16:in `<top (required)>'
        >>  from /Users/jeppe/.rbenv/versions/2.1.5/bin/jekyll:23:in `load'
        >>  from /Users/jeppe/.rbenv/versions/2.1.5/bin/jekyll:23:in `<main>'
        Warning: Please install Jekyll before running this task. Use --force to continue.
        
        Aborted due to warnings.
        
        
        Execution Time (2015-12-08 20:13:45 UTC)
        loading tasks  3.4s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 64%
        jekyll:server  1.9s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 36%
        Total 5.3s Use --force to continue.
            
            Aborted due to warnings.
        

    Execution Time (2015-12-08 20:13:41 UTC)
    loading tasks      2.4s  ▇▇▇▇▇▇▇▇▇▇▇▇ 27%
    concurrent:server  6.3s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 72%
    Total 8.7s
```


### $ grunt serve [FAILS][browserSync_version_error]

```
    $ grunt serve
    Running "serve" task

    Running "clean:server" (clean) task
    >> 1 path cleaned.

    Running "concurrent:server" (concurrent) task
        
        Running "copy:stageCss" (copy) task
        Copied 1 files
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:23:25 UTC)
        loading tasks  3.2s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.2s
            
        Running "coffee:dist" (coffee) task
        >> 0 files created.
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:23:25 UTC)
        loading tasks  3.2s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.2s
            
        Running "sass:server" (sass) task
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:23:25 UTC)
        loading tasks  3.2s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 98%
        sass:server    63ms  ▇ 2%
        Total 3.2s
            
        Running "jekyll:server" (jekyll) task
        `jekyll build --source app --destination .jekyll --config _config.yml` was initiated.
        
        Configuration file: _config.yml
                    Source: app
               Destination: .jekyll
              Generating... 
                            done.
         Auto-regeneration: disabled. Use --watch to enable.
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:23:25 UTC)
        loading tasks  3.2s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 45%
        jekyll:server  3.9s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 55%
        Total 7.1s
        
    Running "autoprefixer:dist" (autoprefixer) task
    File .tmp/css/main.css created.

    Running "browserSync:server" (browserSync) task
    Warning: Cannot read property 'prototype' of undefined Use --force to continue.

    Aborted due to warnings.


    Execution Time (2015-12-08 20:23:23 UTC)
    loading tasks        1.7s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 16%
    concurrent:server    8.2s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 79%
    autoprefixer:dist   176ms  ▇▇▇ 2%
    browserSync:server  346ms  ▇▇▇▇▇▇ 3%
    Total 10.4s
```


### $ sudo npm install grunt-browser-sync --save-dev

```
    $ sudo npm install grunt-browser-sync --save-dev
    Password:
     
    > bufferutil@1.2.1 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/socket.io/node_modules/engine.io/node_modules/ws/node_modules/bufferutil
    > node-gyp rebuild

      CXX(target) Release/obj.target/bufferutil/src/bufferutil.o
      SOLINK_MODULE(target) Release/bufferutil.node
      SOLINK_MODULE(target) Release/bufferutil.node: Finished
    npm WARN package.json node-pre-gyp@0.6.15 No README data
     
    > utf-8-validate@1.2.1 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/socket.io/node_modules/engine.io/node_modules/ws/node_modules/utf-8-validate
    > node-gyp rebuild

      CXX(target) Release/obj.target/validation/src/validation.o
      SOLINK_MODULE(target) Release/validation.node
      SOLINK_MODULE(target) Release/validation.node: Finished

    > bufferutil@1.2.1 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/socket.io/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/ws/node_modules/bufferutil
    > node-gyp rebuild

      CXX(target) Release/obj.target/bufferutil/src/bufferutil.o
      SOLINK_MODULE(target) Release/bufferutil.node
      SOLINK_MODULE(target) Release/bufferutil.node: Finished

    > utf-8-validate@1.2.1 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/socket.io/node_modules/socket.io-client/node_modules/engine.io-client/node_modules/ws/node_modules/utf-8-validate
    > node-gyp rebuild

      CXX(target) Release/obj.target/validation/src/validation.o
      SOLINK_MODULE(target) Release/validation.node
      SOLINK_MODULE(target) Release/validation.node: Finished

    > fsevents@1.0.5 install /Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/chokidar/node_modules/fsevents
    > node-pre-gyp install --fallback-to-build

    [fsevents] Success: "/Users/jeppe/apps/mdd/mdd_yo_jekyll/node_modules/grunt-browser-sync/node_modules/browser-sync/node_modules/chokidar/node_modules/fsevents/lib/binding/Release/node-v14-darwin-x64/fse.node" is installed via remote
    grunt-browser-sync@2.2.0 node_modules/grunt-browser-sync
    └── browser-sync@2.10.0 (ucfirst@1.0.0, async-each-series@0.1.1, longest@1.0.1, emitter-steward@1.0.0, easy-extender@2.3.2, dev-ip@1.0.1, query-string@2.4.2, opn@3.0.3, browser-sync-client@2.4.1, ua-parser-js@0.7.9, portscanner@1.0.0, serve-static@1.10.0, connect@3.4.0, meow@3.3.0, immutable@3.7.5, resp-modifier@5.0.2, foxy@11.1.4, eazy-logger@2.1.2, bs-recipes@1.0.5, serve-index@1.7.2, fs-extra@0.26.2, anymatch@1.3.0, localtunnel@1.8.0, lodash@3.10.1, browser-sync-ui@0.5.16, socket.io@1.3.7, chokidar@1.4.0)
```

### $ grunt serve [SUCCESS]

```
    $ grunt serve
    Running "serve" task

    Running "clean:server" (clean) task
    >> 2 paths cleaned.

    Running "concurrent:server" (concurrent) task
        
        Running "copy:stageCss" (copy) task
        Copied 1 files
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:25:53 UTC)
        loading tasks  4.3s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 4.4s
            
        Running "sass:server" (sass) task
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:25:53 UTC)
        loading tasks  4.3s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 98%
        sass:server    68ms  ▇ 2%
        Total 4.4s
            
        Running "coffee:dist" (coffee) task
        >> 0 files created.
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:25:53 UTC)
        loading tasks  4.4s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 98%
        coffee:dist    79ms  ▇ 2%
        Total 4.5s
            
        Running "jekyll:server" (jekyll) task
        `jekyll build --source app --destination .jekyll --config _config.yml` was initiated.
        
        Configuration file: _config.yml
                    Source: app
               Destination: .jekyll
              Generating... 
                            done.
         Auto-regeneration: disabled. Use --watch to enable.
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:25:53 UTC)
        loading tasks  4.4s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 53%
        jekyll:server  3.9s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 47%
        Total 8.3s
        
    Running "autoprefixer:dist" (autoprefixer) task
    File .tmp/css/main.css created.

    Running "browserSync:server" (browserSync) task
    [BS] Access URLs:
     ----------------------------------
           Local: http://localhost:3000
        External: http://10.0.1.4:3000
     ----------------------------------
              UI: http://localhost:3001
     UI External: http://10.0.1.4:3001
     ----------------------------------
    [BS] Serving files from: .jekyll
    [BS] Serving files from: .tmp
    [BS] Serving files from: app
    [BS] Watching files...

    Running "watch" task
    Waiting...
```


### $ grunt deploy [FAILS due to double quotes]

```
    $ grunt deploy
    Running "clean:server" (clean) task
    >> 2 paths cleaned.

    Running "jekyll:check" (jekyll) task
    `jekyll doctor --source app` was initiated.

    Configuration file: none
      Your test results are in. Everything looks fine.

    Running "sass:server" (sass) task

    Running "coffeelint:check" (coffeelint) task
    >> 0 files lint free.

    Running "coffee:dist" (coffee) task
    >> 0 files created.

    Running "jshint:all" (jshint) task

    Gruntfile.js
      line 63  col 24  Strings must use singlequote.
      line 64  col 21  Strings must use singlequote.
      line 65  col 34  Strings must use singlequote.
      line 74  col 42  Strings must use singlequote.
      line 91  col 24  Strings must use singlequote.
      line 92  col 21  Strings must use singlequote.
      line 93  col 34  Strings must use singlequote.

    ✖ 7 problems

    Warning: Task "jshint:all" failed. Use --force to continue.

    Aborted due to warnings.


    Execution Time (2015-12-08 20:39:46 UTC)
    loading tasks     3s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 46%
    jekyll:check    3.3s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 50%
    jshint:all     212ms  ▇▇▇▇▇▇ 3%
    Total 6.6s
```


### $ grunt deploy [SUCCESS]

```
    $ grunt deploy
    Running "clean:server" (clean) task
    >> 1 path cleaned.

    Running "jekyll:check" (jekyll) task
    `jekyll doctor --source app` was initiated.

    Configuration file: none
      Your test results are in. Everything looks fine.

    Running "sass:server" (sass) task

    Running "coffeelint:check" (coffeelint) task
    >> 0 files lint free.

    Running "coffee:dist" (coffee) task
    >> 0 files created.

    Running "jshint:all" (jshint) task

    ✔ No problems


    Running "csslint:check" (csslint) task
    >> 1 file lint free.

    Running "clean:dist" (clean) task
    >> 11 paths cleaned.

    Running "clean:server" (clean) task
    >> 0 paths cleaned.

    Running "jekyll:dist" (jekyll) task
    `jekyll build --source app --destination dist --config _config.yml,_config.build.yml` was initiated.

    Configuration file: _config.yml
    Configuration file: _config.build.yml
           Deprecation: The 'pygments' configuration option has been renamed to 'highlighter'. Please update your config file accordingly. The allowed values are 'rouge', 'pygments' or null.
                Source: app
           Destination: dist
          Generating... 
                        done.
     Auto-regeneration: disabled. Use --watch to enable.

    Running "concurrent:dist" (concurrent) task
        
        Running "coffee:dist" (coffee) task
        >> 0 files created.
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:45:29 UTC)
        loading tasks  3.7s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.7s
            
        Running "sass:dist" (sass) task
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:45:29 UTC)
        loading tasks  3.7s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 99%
        Total 3.7s
            
        Running "copy:dist" (copy) task
        Copied 2 files
        
        Done, without errors.
        
        
        Execution Time (2015-12-08 20:45:29 UTC)
        loading tasks   3.7s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 94%
        copy:dist      243ms  ▇▇▇ 6%
        Total 4s
        
    Running "useminPrepare:html" (useminPrepare) task
    Going through dist/index.html to update the config
    Looking for build script HTML comment blocks

    Configuration is now:

      concat:
      { generated: 
       { files: 
          [ { dest: '.tmp/concat/css/main.css',
              src: 
               [ '{app,.tmp}/_bower_components/normalize-css/normalize.css',
                 '{app,.tmp}/css/main.css' ] },
            { dest: '.tmp/concat/js/head-scripts.js',
              src: [ '{app,.tmp}/_bower_components/modernizr/modernizr.js' ] },
            { dest: '.tmp/concat/js/script.js',
              src: [ '{app,.tmp}/js/plugins.js', '{app,.tmp}/js/main.js' ] } ] } }

      uglify:
      { generated: 
       { files: 
          [ { dest: 'dist/js/head-scripts.js',
              src: [ '.tmp/concat/js/head-scripts.js' ] },
            { dest: 'dist/js/script.js',
              src: [ '.tmp/concat/js/script.js' ] } ] } }

      cssmin:
      { dist: { options: { check: 'gzip' } },
      generated: 
       { files: 
          [ { dest: 'dist/css/main.css',
              src: [ '.tmp/concat/css/main.css' ] } ] } }

    Running "concat:generated" (concat) task
    File .tmp/concat/css/main.css created.
    File .tmp/concat/js/head-scripts.js created.
    File .tmp/concat/js/script.js created.

    Running "cssmin:dist" (cssmin) task

    Running "cssmin:generated" (cssmin) task
    File dist/css/main.css created: 13.1 kB → 3.29 kB

    Running "autoprefixer:dist" (autoprefixer) task
    File .tmp/concat/css/main.css created.

    Running "uglify:generated" (uglify) task

    Running "imagemin:dist" (imagemin) task
    Minified 1 image (saved 0 B)

    Running "svgmin:dist" (svgmin) task
    Total saved: 0 B

    Running "filerev:dist" (filerev) task
    ✔ dist/js/head-scripts.js changed to head-scripts.32fa.js
    ✔ dist/js/script.js changed to script.d16b.js
    ✔ dist/css/main.css changed to main.d92f.css

    Running "usemin:html" (usemin) task

    Processing as HTML - dist/404.html
    Update the HTML to reference our concat/min/revved script files
    Update the HTML with the new css filenames
    Update the HTML with the new img filenames
    Update the HTML with the new video filenames
    Update the HTML with the new poster filenames
    Update the HTML with the new source filenames
    Update the HTML with data-main tags
    Update the HTML with data-* tags
    Update the HTML with background imgs, case there is some inline style
    Update the HTML with anchors images
    Update the HTML with reference in input
    Update the HTML with the new img filenames in meta tags
    Update the HTML with the new object filenames
    Update the HTML with the new image filenames for svg xlink:href links
    Update the HTML with the new image filenames for src links

    Processing as HTML - dist/index.html
    Update the HTML to reference our concat/min/revved script files
    <script src="/js/head-scripts.js" changed to <script src="/js/head-scripts.32fa.js"
    <script src="/js/script.js" changed to <script src="/js/script.d16b.js"
    Update the HTML with the new css filenames
    <link rel="stylesheet" href="/css/main.css" changed to <link rel="stylesheet" href="/css/main.d92f.css"
    Update the HTML with the new img filenames
    Update the HTML with the new video filenames
    Update the HTML with the new poster filenames
    Update the HTML with the new source filenames
    Update the HTML with data-main tags
    Update the HTML with data-* tags
    Update the HTML with background imgs, case there is some inline style
    Update the HTML with anchors images
    Update the HTML with reference in input
    Update the HTML with the new img filenames in meta tags
    Update the HTML with the new object filenames
    Update the HTML with the new image filenames for svg xlink:href links
    Update the HTML with the new image filenames for src links

    Processing as HTML - dist/jekyll/update/2015/12/08/yo-jekyllrb.html
    Update the HTML to reference our concat/min/revved script files
    <script src="/js/head-scripts.js" changed to <script src="/js/head-scripts.32fa.js"
    <script src="/js/script.js" changed to <script src="/js/script.d16b.js"
    Update the HTML with the new css filenames
    <link rel="stylesheet" href="/css/main.css" changed to <link rel="stylesheet" href="/css/main.d92f.css"
    Update the HTML with the new img filenames
    Update the HTML with the new video filenames
    Update the HTML with the new poster filenames
    Update the HTML with the new source filenames
    Update the HTML with data-main tags
    Update the HTML with data-* tags
    Update the HTML with background imgs, case there is some inline style
    Update the HTML with anchors images
    Update the HTML with reference in input
    Update the HTML with the new img filenames in meta tags
    Update the HTML with the new object filenames
    Update the HTML with the new image filenames for svg xlink:href links
    Update the HTML with the new image filenames for src links

    Running "usemin:css" (usemin) task

    Processing as CSS - dist/css/main.d92f.css
    Update the CSS to reference our revved images

    Running "htmlmin:dist" (htmlmin) task
    Minified dist/404.html 1.41 kB → 1.3 kB
    Minified dist/index.html 1.63 kB → 1.5 kB
    Minified dist/jekyll/update/2015/12/08/yo-jekyllrb.html 1.77 kB → 1.62 kB

    Running "buildcontrol:dist" (buildcontrol) task

    Creating remote.

    No changes to your branch. Skipping commit.

    Pushing gh-pages to https://github.com/Djarnis/yo-jekyllrb.git
    To https://github.com/Djarnis/yo-jekyllrb.git
     * [new branch]      gh-pages -> gh-pages

    Done, without errors.


    Execution Time (2015-12-08 20:45:20 UTC)
    loading tasks       2.2s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 10%
    jekyll:check        2.8s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 12%
    jekyll:dist         2.9s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 12%
    concurrent:dist     4.7s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 20%
    uglify:generated   412ms  ▇▇▇ 2%
    buildcontrol:dist   8.9s  ▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇ 39%
    Total 23s
```

