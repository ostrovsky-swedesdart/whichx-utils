[![npm](https://img.shields.io/npm/dt/brain.js.svg?style=flat-square)](https://npmjs.com/package/whichx-utils) [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com)

<h1><p style="text-align: center" align="center">WhichX-utils</p></h1>

A package, with tools designed to work with strings, numbers, and mathematics.

## Usage get port
```js
import { port } from "whichx-utils";

const body = port.default({
Types: [
{
    port: 80
}
],
config: {}
});

console.log(body) // { type: "HTTP" }
```

## Usage MessageFrom
```js
import { MessageFrom } from "whichx-utils";

const body = MessageFrom("привет");

console.log(body) // Привет.
```

## Usage to getLast
```js
import { getLast } from "whichx-utils";

const body = ["привет", "здравствуй"].getLast();

console.log(body) // здравствуй
```

## Usage to WhileUtils
```js
import { whileUtils } from "whichx-utils";

const body = whileUtils("url in vkhost.github.io");

console.log(body) // ...
```

## Support

<p style="text-align: center" align="center"><a href="https://qiwi.com/p/NODEJSLUPUS"><img scr="https://sun9-83.userapi.com/impg/9JsEyB1iBNukDvQ2k8Vf_jeXNA9fx1Fk3TuhDw/T98hP8JqGug.jpg?size=604x352&quality=96&sign=abfbfb49bd388a2ec020bd96cc7fd62f&c_uniq_tag=u7e5F1ZhrxdV8g2hOAhNEAbdTz-htHPSQlxWCQEoMJk&type=album">Пожертвовать / Support</img></a></p>
<p style="text-align: center" align="center">Ник QIWI: NODEJSLUPUS</p>