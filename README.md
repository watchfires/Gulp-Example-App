# Gulp Example App

This is a very simple example app that utilizes Gulp to automate the following tasks:

* Logging a message to the console

* Copying all HTML files from the `src` folder to the `dist` folder

* Optimizing images

* Compiling Sass

* Concatenating JavaScript files

* Running all of the above tasks at once

* Watching all of the above tasks

<br>

It utilizes the following dependencies:

* [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)

* [gulp-sass](https://www.npmjs.com/package/gulp-sass)

* [gulp-concat](https://www.npmjs.com/package/gulp-concat)

* [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)

<br>

It was made from a Traversy Media YouTube [video](https://youtu.be/1rw9MfIleEg).

<br>

## Installation

From within the project directory, install the dependencies.

```
$ npm install
```

<br>

## Commands

_Log a message to the console_:

```
$ gulp message
```

_Copy all HTML files_:

```
$ gulp copyHTML
```

_Optimize images_:

```
$ gulp imageMin
```


_Minify JavaScript files_:

```
$ gulp minify
```

_Compile Sass_:

```
$ gulp sass
```

_Concatenate JavaScript files_:

```
$ gulp scripts
```

_Run all tasks_:

```
$ gulp
```

_Watch all tasks_:

```
$ gulp watch
```