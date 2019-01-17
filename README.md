# Build-Setup

General web development build and workflow.

&nbsp;

## Overview

This repository servers as a template for your development process by automating certain tasks through the use of [gulp](https://gulpjs.com/).

By default, the `gulpfile.js` has the following tasks:

| Tasks           | Description                                                                                |
| --------------- | ------------------------------------------------------------------------------------------ |
| `compileMarkup` | Minify your html files.                                                                    |
| `compileStyle`  | Convert and minify your scss files to css with added prefixes and generate a sourcemap.    |
| `compileScript` | Concat and minify your javascript files.                                                   |
| `compileImages` | Minify your images through optimization.                                                   |
| `startServer`   | Initiate a server.                                                                         |
| `watchFiles`    | Monitor your source files and update the build folder base upon any changes that are made. |





&nbsp;

## Setup

First, download or clone this repository.

Then ensure that you you have `gulp-cli` installed globally to be able to run the `gulp` command in your terminal.

```
npm i/install gulp-cli -g
```

&nbsp;

Next install the dev dependencies from the package.json through:

```
$ npm i/install
```

&nbsp;

Remove any unwanted packages by simply removing it from the package.json prior to the installing above. Or by running the command below after installing the packages from the json.

```
$ npm uninstall <package_name>
```

Note that if you are to remove a package that is being utilized, you would have to modify the `gulpfile.js` and remove that packages function within it's designated task.

&nbsp;

Run `gulp` to commence the specified tasks.

```
$ gulp
```

&nbsp;

Finally open up the `src` folder to construct your web site/application, and a build folder will be generated, and built upon through out your process to be shipped for production. Happy coding :)
