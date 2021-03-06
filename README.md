# Splash Website
Test project for Splash.

![Splash](screenshot.jpg)

## Built With
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [SASS](https://sass-lang.com/)
- [jQuery](https://jquery.com/)

## Requirements
 - NPM
 - Gulp.js
 - Rellax.js

## Install
```
    $ git clone git@github.com:samiiexx/splash.git main
    $ cd main
    $ npm install
```

## Running the project
Production directory is the `public` folder.\
\
Run a full build
```
gulp all
```
Watch files and run BrowserSync
```
gulp serve
```
### Individual Tasks
These tasks can be run individually.\
\
Include HTML partials
```
gulp html
```
Compile SASS, browser autoprefix and minify CSS
```
gulp style
```
Compile, transpile and minify JS
```
gulp js
```
Minify images
```
gulp image
```

## Contributors
- Favour Samuel (@samiiexx)

## License
Copyright (c) 2021 Favour Samuel.

For enquiries please contact me at [favour@starboxtech.com](mailto:favour@starboxtech.com).