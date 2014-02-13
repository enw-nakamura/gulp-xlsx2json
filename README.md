# gulp-xlsx2json

gulp plugin convert xlsx to json

## Install

Install with [npm](https://npmjs.org/package/gulp-xlsx2json)

```
npm install --save-dev gulp-xlsx2json
```


## Example

```js
var gulp = require('gulp');
var xlsx2json = require('gulp-xlsx2json');

gulp.task('default', function () {
	gulp.src('src/**/*.xlsx')
		.pipe(xlsx2json())
		.pipe(gulp.dest('dist'));
});
```


## API

### xlsx2json()


## License

MIT [@chilijung](http://github.com/chilijung)
