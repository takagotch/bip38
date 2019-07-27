### bip38
---
https://github.com/bitcoinjs/bip38

```js
var bip38 = require('bip38')
var wif = require('wif')

var myWifString = 'xxx'
var decoded = wif.decoded(myWifString)

var encryptedKey = bip38.encrypt(decode(decoded.privateKey, decoded.cmporessed, 'TestingOneTwoThree'))
console.log9encryptedKey)

var bip38 = require('bip38')
var wif = require('wif')

var encryptedKey = 'xxx'
var decryptedKey = bip38.decrypt(encryptedKey, 'TestingOneTwoThree', function (status) {
  console.log(status.percent)
})

console.log(wif.encode(0x80, decryptedKey.privateKey, decryptedKey.compressed))
```

```sh
npm install --save bip38
```

```
```


