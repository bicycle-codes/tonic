<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/socketsupply/tonic/master/readme-tonic-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/socketsupply/tonic/master/readme-tonic.png">
  <img alt="tonic" src="https://raw.githubusercontent.com/socketsupply/tonic/master/readme-tonic.png">
</picture>

<p align="center">
  https://tonicframework.dev
</p>
<br/>
<br/>

A fork of [@socketsupply/tonic](https://github.com/socketsupply/tonic)

![tests](https://github.com/nichoth/tonic/actions/workflows/nodejs.yml/badge.svg)
[![Socket Badge](https://socket.dev/api/badge/npm/package/@nichoth/tonic)](https://socket.dev/npm/package/@nichoth/tonic)
[![module](https://img.shields.io/badge/module-ESM%2FCJS-blue)](README.md)
![license](https://img.shields.io/badge/license-MIT-brightgreen)


Tonic is a low profile component framework for the web. It's one file, less than 3kb gzipped and has no dependencies. It's designed to be used with modern Javascript and is compatible with all modern browsers and built on top of the Web Components.

## Installation

```sh
npm install @nichoth/tonic
```

## Usage

```js
import Tonic from '@nichoth/tonic'

class MyGreeting extends Tonic {
  render () {
    return this.html`<div>Hello, World.</div>`
  }
}

Tonic.add(MyGreeting, 'my-greeting')
```

After adding your Javascript to your HTML, you can use your component anywhere.

```html
<html>
  <head>
    <script src="my-greeting.js"></script>
  </head>
  <body>
    <my-greeting></my-greeting>
  </body>
</html>
```

# Useful links
- [Tonic components](https://github.com/socketsupply/components)
- [Migration from the early versions of Tonic](./MIGRATION.md)
- [API](./API.md)
- [Troubleshooting](./HELP.md)

MIT License
 
