# compress-image

> Minify image  using [tinypng](https://tinypng.com/)



## Install

Install with [npm](https://npmjs.org/package/compress-image)

```
npm install --save-dev compressimg
```


## Example

```js
var compressImage = require('compressimg');

compressImage('inputDir','outputDir',{
	tinifyApiKey: 'xxxxxxx', // tinypng developer apikey
	compresssPercent: 10, // limit compress scale
	compressLimitCount: 5 // limit compress count
});
```


## License

MIT © [zhiyingzzhou](https://github.com/zhiyingzzhou)
