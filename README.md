# Build-Setup

General web development build

&nbsp;

## Setup:

Install the dev dependencies from the package.json through:

```
$ npm i/install
```

&nbsp;

Remove any unwanted packages by simply removing it from the package.json prior to the installing above. Or by running the command below after installing the packages from the json.

```
$ npm uninstall <package_name>
```

Note that if you are to remove a package that is being utilized, you would have to modify the `gulpfile` and remove that packages function in the designated task.

&nbsp;

Run `gulp` to initiate the specified tasks.

```
$ npm gulp
```

&nbsp;

Finally open up the `src` folder to construct your web site/application, and a build folder will be generated, and built upon through out your process to be shipped for production. Happy coding :)
