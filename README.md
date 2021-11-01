# js-obfuscator




## Example 


```js
var axios = require("axios")

var code = `console.log('hello world')` 
result = (await axios('https://api.clph.me/api/javascript-obfuscator?apikey=YOUR-APIKEY', { method: 'POST', data: new URLSearchParams(Object.entries({ code })) })).data
console.log(result)
```
