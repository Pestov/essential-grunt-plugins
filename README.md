#HTML&CSS
[autoprefixer](https://github.com/postcss/autoprefixer) - parse CSS and add vendor prefixes to rules by Can I Use.

[grunt-browser-sync](https://github.com/BrowserSync/grunt-browser-sync) - keep multiple browsers & devices in sync when building websites.

[grunt-html-build](https://github.com/spatools/grunt-html-build) and [grunt-include-replace](https://github.com/alanshaw/grunt-include-replace) - appends scripts and styles, removes debug parts, append html partials.

[grunt-email-design](https://github.com/leemunroe/grunt-email-design) - a workflow for designing and testing HTML email templates.

[grunt-uncss](https://github.com/addyosmani/grunt-uncss) and [grunt-ucss](https://github.com/ullmark/grunt-ucss) - remove unused CSS from your projects.

[grunt-contrib-cssmin](https://github.com/gruntjs/grunt-contrib-cssmin) - compress CSS files.

[grunt-revizor](https://github.com/atrolov/grunt-revizor) - compress CSS classes and identifiers. In addition, there are many CSS optimizers and [benchmark tests](http://goalsmashers.github.io/css-minification-benchmark/) ([GitHub](https://github.com/GoalSmashers/css-minification-benchmark) for them. But recently I saw most powerful [Shorthand](https://github.com/frankmarineau/shorthand) utility without Grunt, which does folowing:
```
a {
	font-family: Arial;
	font-style: italic;
	font-size: 14px;
	line-height: 18px; 
	font-weight: bold;
    background-image: url('example.png');
    background-color: red;
    background-size: cover;
    background-repeat: no-repeat;
}

=>

a {
  font: italic bold 14px/18px Arial;
  background: red url('example.png') no-repeat / cover;
}
```

[grunt-contrib-htmlmin](https://github.com/gruntjs/grunt-contrib-htmlmin) - neat HTML minificator. 

[grunt-penthouse](https://github.com/fatso83/grunt-penthouse) and [grunt-criticalcss](https://github.com/filamentgroup/grunt-criticalcss) - automatically find the Critical Path in your project. 

[grunt-csscomb](https://github.com/csscomb/grunt-csscomb) - refines the structure of your CSS. 

[grunt-styleguide](https://github.com/indieisaconcept/grunt-styleguide) - generate styleguides.

[grunt-contrib-csslint](https://www.npmjs.com/package/grunt-contrib-csslint) - CSS linter. 

[grunt-html](https://github.com/jzaefferer/grunt-html) - HTML validator based on validator from W3C.

#JavaScript
[grunt-autopolyfiller](https://github.com/azproduction/grunt-autopolyfiller/) - precise polyfills. This is like Autoprefixer, but for JavaScript polyfills. 

[grunt-babel](https://github.com/babel/babel) - transpiler for writing next generation JavaScript.

[grunt-jsfmt](https://github.com/james2doyle/grunt-jsfmt) - for formatting, searching, and rewriting JavaScript.

[grunt-jscs](https://github.com/jscs-dev/grunt-jscs) - for checking JavaScript Code Style.

[grunt-modernizr](https://github.com/Modernizr/grunt-modernizr) - build out a lean, mean Modernizr machine.

[grunt-express](https://github.com/blai/grunt-express) - start (and supervise) an Express.js web server using, works well with socket.io

[grunt-contrib-requirejs](https://github.com/gruntjs/grunt-contrib-requirejs) and [grunt-browserify](https://github.com/jmreidy/grunt-browserify) - optimize the work with RequireJS and Browserify respectively.

[grunt-shipit](https://github.com/shipitjs/grunt-shipit) - [Shipit](https://github.com/shipitjs/shipit) automation and deployment tool.

[grunt-plato](https://github.com/jsoverson/grunt-plato) - generate static analysis reports.

[grunt-complexity](https://github.com/vigetlabs/grunt-complexity) - evaluates code maintainability using Halstead and Cyclomatic metrics.

[fixmyjs](https://github.com/jonschlinkert/grunt-fixmyjs) - automatically fix silly lint errors with help of [JSHint](http://jshint.com/) ([grunt-contrib-jshint](https://github.com/gruntjs/grunt-contrib-jshint)).

[grunt-jscpd](https://github.com/kucherenko/jscpd) - copy/paste detector for programming source code.

[grunt-jsonlint](https://github.com/brandonramirez/grunt-jsonlint) and [grunt-yamllint](https://github.com/geedew/grunt-yamllint) - JSON and YAML validators.

[grunt-contrib-uglify](https://github.com/gruntjs/grunt-contrib-uglify) - JavaScript compressor. 

[grunt-contrib-concat](https://github.com/gruntjs/grunt-contrib-concat) - concatenate files. 

###Unit Tests
* [grunt-contrib-nodeunit](https://github.com/gruntjs/grunt-contrib-nodeunit)
* [grunt-contrib-jasmine](https://github.com/gruntjs/grunt-contrib-jasminen)
* [grunt-contrib-qunit](https://github.com/gruntjs/grunt-contrib-qunit)
* [grunt-mocha](https://github.com/kmiyashiro/grunt-mocha)
* [grunt-karma](https://github.com/karma-runner/grunt-karma) 

#Graphics
[grunticon](https://github.com/filamentgroup/grunticon) - mystical CSS icon solution.

[grunt-webfont](SVG to webfont converter) - SVG to webfont converter.

[grunt-responsive-images](https://github.com/andismith/grunt-responsive-images) - produce images at different sizes for responsive websites.

[grunt-sharp](https://www.npmjs.com/package/grunt-sharp) - fastest module for work JPEG, PNG, WebP and TIFF images.

[grunt-svgstore](https://github.com/FWeinb/grunt-svgstore) - merge SVGs from a folder.

[imacss](https://github.com/akoenig/imacss) - application and library that transforms image files to data URIs. 

[grunt-contrib-imagemin](https://github.com/gruntjs/grunt-contrib-imagemin), [grunt-imageoptim](https://github.com/JamieMason/grunt-imageoptim) and [grunt-tinypng](https://github.com/marrone/grunt-tinypng) for image compression.

[grunt-spritesmith](https://github.com/Ensighten/grunt-spritesmith) - converting a set of images into a spritesheet and corresponding CSS variables.


#Others
[assemble](https://github.com/assemble/assemble) - static site generator.

[jit-grunt](https://github.com/shootaroo/jit-grunt) - JIT(Just In Time) loader. 

[grunt-gulp](https://github.com/shama/grunt-gulp)- allows to start Gulp plugins for Grunt.

[grunt-contrib-watch](https://github.com/gruntjs/grunt-contrib-watch) - run tasks whenever watched files change.

[grunt-notify](https://github.com/dylang/grunt-notify) - automatic error messages in system notifications center when Grunt tasks fail.

[grunt-git](https://github.com/rubenv/grunt-git) - able to use Git commands.

[grunt-githooks](https://github.com/wecodemore/grunt-githooks) - bind Grunt tasks to Git Hooks. 

[grunt-gitbook](https://github.com/GitbookIO/grunt-gitbook) - create documentation by GitBook.

[grunt-jsdoc](https://github.com/krampstudio/grunt-jsdoc) - generate JavaScript documentation by running JSDoc3.

[grunt-rev](https://github.com/cbas/grunt-rev) - static file asset revisioning through content hashing.

[grunt-release](https://github.com/geddski/grunt-release) and [grunt-version](https://github.com/kswedberg/grunt-version) - allows to manage versions of a project.

[grunt-conventional-changelog](https://github.com/btford/grunt-conventional-changelog) - generating a changelog from Git metadata. Also there are [grunt-bump](https://github.com/vojtajina/grunt-bump), which increments versions in package JSON and [grunt-dev-update](https://github.com/pgilad/grunt-dev-update), which automatically updates packages.

[grunt-wiredep](https://github.com/stephenplusplus/grunt-wiredep) - inject Bower packages.

[grunt-remove-logging](https://github.com/ehynds/grunt-remove-logging) - remove console logging statements.

[grunt-proxy](https://github.com/tutukin/grunt-proxy) and [grunt-connect-proxy](https://github.com/drewzboto/grunt-connect-proxy) - connect support for proxying API calls during development.

[grunt-phantomas](https://github.com/stefanjudis/grunt-phantomas) - measure frontend performance. 

[grunt-preprocess](https://github.com/jsoverson/grunt-preprocess) - preprocess files based off environment configuration. 

[time-grunt](https://github.com/sindresorhus/time-grunt) - displays the elapsed execution time of grunt tasks.

[load-grunt-config](https://github.com/firstandthird/load-grunt-config) - Grunt library that allows you to break up your Gruntfile config by task.

[grunt-newer](https://github.com/tschaub/grunt-newer) - run Grunt tasks with only those source files modified since the last successful run.

[grunt-open](https://github.com/jsoverson/grunt-open) - open URLs and files. 

[grunt-contrib-connect](https://github.com/gruntjs/grunt-contrib-connect) - simple static web server. 

[grunt-exec](https://github.com/jharding/grunt-exec) and [grunt-shell](https://github.com/sindresorhus/grunt-shell) - run Shell commands.

[grunt-ssh](https://github.com/chuckmo/grunt-ssh) - provides the ability to connect via SSH and SFTP.

[grunt-contrib-compress](https://github.com/gruntjs/grunt-contrib-compress) - compress files and folders.

[grunt-contrib-clean](https://github.com/gruntjs/grunt-contrib-clean) and [grunt-contrib-copy](https://github.com/gruntjs/grunt-contrib-copy) - respectively remove and copy sources. 

[grunt-usebanner](https://github.com/mattstyles/grunt-banner) - adds a simple banner (copyright or ASCII headers) to source files and [grunt-figlet](https://github.com/patorjk/grunt-figlet) for help for it.

[grunt-file-info](https://github.com/hansifer/grunt-file-info) - displays sizes and versions of files in a readable format.

#Compilers
* [grunt-contrib-less](https://github.com/gruntjs/grunt-contrib-less) - LESS in CSS.
* [grunt-contrib-sass](https://github.com/gruntjs/grunt-contrib-sass) and [grunt-sass](https://github.com/sindresorhus/grunt-sass) - SASS/SCSS in СSS.
* [grunt-contrib-compass](https://github.com/gruntjs/grunt-contrib-compass) - SASS with Compass in CSS.
* [grunt-contrib-stylus](https://github.com/gruntjs/grunt-contrib-stylus) - Stylus in CSS.
* [grunt-contrib-coffee](https://github.com/gruntjs/grunt-contrib-coffee) - CoffeeScript in JavaScript.
* [grunt-contrib-jade](https://github.com/gruntjs/grunt-contrib-jade) - Jade in HTML.
* [grunt-contrib-handlebars](https://github.com/gruntjs/grunt-contrib-handlebars) - Handlebars templates in JST.
* [grunt-contrib-jst](https://github.com/gruntjs/grunt-contrib-jst) - Underscore templates in JST.
* [grunt-react](https://github.com/ericclemmons/grunt-react) - Facebook React's JSX templates in JST.
* [grunt-nunjucks](https://github.com/jlongster/grunt-nunjucks) - Nunjucks templates in JST. 
* [grunt-dustjs](https://github.com/STAH/grunt-dustjs) - Dust templates in JST.
* [grunt-html2js](https://github.com/karlgoldstein/grunt-html2js) - AngularJS templates in JST.

#Finally
* [psi](https://github.com/addyosmani/psi) - PageSpeed Insights with reporting.
* [tmi](https://github.com/addyosmani/tmi) -  TMI (Too Many Images) - discover your image weight on the web.
* [ngrok](https://ngrok.com/) - Introspected tunnels to localhost.
* [pageres](https://github.com/sindresorhus/pageres) - responsive website screenshots. 
* [matchdep](https://github.com/tkellen/node-matchdep) -  filter npm module dependencies.
* Maybe some automatization methods you want to use directly in the editor, so look at the [The Best Plugins for Sublime Text](http://ipestov.com/the-best-plugins-for-sublime-text/). 



