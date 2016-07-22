# seed-dash [![npm version](https://badge.fury.io/js/seed-color-scheme.svg)](https://badge.fury.io/js/seed-color-scheme)

dash other pack for [Seed](https://github.com/helpscout/seed)!

## Install
```
npm install seed-dash --save-dev
```


## Basic Usage

### SCSS
This seed pack needs to be imported into your sass pipeline. Below is an example using Gulp:


```javascript
var gulp = require('gulp');
var sass = require('gulp-sass');
var pack = require('seed-dash');

gulp.task('sass', function () {
  return gulp.src('./sass/**/*.scss')
    .pipe(sass({
      includePaths: pack
    }))
    .pipe(gulp.dest('./css'));
});
```

Once that is setup, simply `@import` *seed-dash* as needed in your `.scss` file:

```sass
// Packs
@import "pack/seed-dash/_index";
```

## Options

The following variables can be found in `_config.scss`

```sass
seed-dash config options
```