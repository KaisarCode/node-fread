# Fread
[nodejs] fs.readFile wrapper.

### Install
```
npm install kc-fread
```

### Use
```js
var fread = require('kc-fread');
var str   = fread('my-file.txt');
console.log(str);

## Async usage
fread('my-file.txt', function(err, str){
    console.log(data);
});
```
