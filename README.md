# js-obfuscator




## Example 1


```js
var axios = require("axios")

var code = `console.log('hello world')` 
result = (await sios('https://api.clph.me/api/javascript-obfuscator?apikey=caliphganz', { method: 'POST', data: new URLSearchParams(Object.entries({ code })) })).data
console.log(result)
```
