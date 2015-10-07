# Getting Started

#### 1. Install gulp globally:

```sh
$ npm install --global gulp
```
**Note:** You may need to use sudo only for OSX, *nix, BSD etc and run your command shell as Administrator (for Windows)

#### 2. Install gulp in your project devDependencies:

```sh
$ npm install --save-dev gulp
```

#### 3. Create a `gulpfile.js` at the root of your project:

```js
var gulp = require('gulp');

gulp.task('default', function() {
  // place code for your default task here
});
```

#### 4. Run gulp:

```sh
$ gulp
```

The default task will run and do nothing.

To run individual tasks, use `gulp <task> <othertask>`.

## Where do I go now?

You have an empty gulpfile and everything is installed. How do you REALLY get started? Check out the [recipes](recipes) and the [list of articles](README.md#articles) for more information.

## .src, .watch, .dest, CLI args - How do I use these things?

For API specific documentation you can check out the [documentation for that](API.md).

## Available Plugins

The gulp community is growing, with new plugins being added daily. See the [main website](http://gulpjs.com/plugins/) for a complete list.
