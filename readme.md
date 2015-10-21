# gulp-sp-wsp [![Build Status](https://travis-ci.org/dimkk/gulp-sp-wsp.svg?branch=master)](https://travis-ci.org/dimkk/gulp-sp-wsp)

> My stellar gulp plugin


## Install

```
$ npm install --save-dev gulp-sp-wsp
```


## Usage

```js
var gulp = require('gulp');
var spWsp = require('gulp-sp-wsp');

gulp.task('default', function () {
	return gulp.src('src/file.ext')
		.pipe(spWsp())
		.pipe(gulp.dest('dist'));
});
```


## API

### spWsp(options)

#### options

##### foo

Type: `boolean`  
Default: `false`

Lorem ipsum.


## License

MIT © [dimkk](https://github.com/dimkk)
