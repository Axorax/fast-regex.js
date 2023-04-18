<p align="center"><img src="https://raw.githubusercontent.com/Axorax/fast-regex.js/main/fastRegex.svg"></p>

<p align="center">Premade <strong>regex</strong> templates</p>

<p align="center">Free and <a href="https://github.com/Axorax/fast-regex.js">open-source for anyone to contribute</a>!</p>

## 🔮 JavaScript Support

| Type     | Support |
| -------- | ------- |
| commonjs | ✅     |
| ES6      | ✅     |
| Browser  | ✅     |

<br>

## ⚙️ Installation

```js
npm i fast-regex
```

**CDN Links:**

- https://www.unpkg.com/fast-regex@1.1.1/fastRegex.js

- https://cdn.jsdelivr.net/npm/fast-regex@1.1.1/fastRegex.js

If you are using npm to install it and then running it on the browser then use:

```js
import fastRegex from './node_modules/fast-regex/fastRegex.js';
```

## 📖 Documentation

#### ▸ Example code:

```js
import { fastRegex } from 'fast-regex';

console.log(fastRegex('hasAlphanumeric').test('Hello world!'));

console.log(fastRegex('imgSrc').exec('<img src="hello-world.png">'));
```

#### ▸ Add your own regex:

```js
fastRegex({
    name: 'myCoolRegex',
    regex: '[0-2]'
});

console.log(fastRegex('myCoolRegex').test('69'));
```

#### ▸ Add your own regex with flags:

```js
fastRegex({
    name: 'myCoolRegexWithFlags',
    regex: '[a-z]',
    flags: 'g'
});
```

#### ▸ All regex codes:

```js
fastRegex('validEmail')
fastRegex('ipv4')
fastRegex('ipv6')
fastRegex('hasInteger')
fastRegex('hasAlphanumeric')
fastRegex('validPhone')
fastRegex('imgSrc')
fastRegex('validZipCode')
fastRegex('validTwitterUsername')
fastRegex('domain')
fastRegex('removeHtmlComments')
fastRegex('isPositiveInteger')
fastRegex('isNegativeInteger')
fastRegex('validCreditCard')
```

---

[Support me on Patreon](https://www.patreon.com/axorax) - 
[Check out my socials](https://github.com/axorax/socials)