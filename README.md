# js-obfuscator


```js
var axios = require("axios");

var code = `console.log('hello world')`;
result = (await axios('https://caliphapi.com/api/javascript-obfuscator?apikey=YOUR-APIKEY', { method: 'POST', data: new URLSearchParams(Object.entries({ code })) })).data;
console.log(result);
```




# Binary

### encrypt 
```js
var axios = require("axios");

var string = `hello world`;
result = (await axios('https://caliphapi.com/api/binary/enc?apikey=YOUR-APIKEY', { method: 'POST', data: new URLSearchParams(Object.entries({ string })) })).data;
console.log(result.result);
```

### decrypt 
```js
var axios = require("axios");

var string = `1101000 1100101 1101100 1101100 1101111 100000 1110111 1101111 1110010 1101100 1100100`;
result = (await axios('https://caliphapi.com/api/binary/dec?apikey=YOUR-APIKEY', { method: 'POST', data: new URLSearchParams(Object.entries({ string })) })).data;
console.log(result.result);
```


# Rangkum

  Coming Soon




# Get Apikey

* [`Register Account`](https://caliphapi.com/users/register)
* [`Buy APIKEY`](https://wa.me/62882003806038?text=min%20mau%20beli%20apikey)

# Documentation
* [`Docs`](https://caliphapi.com/docs)
