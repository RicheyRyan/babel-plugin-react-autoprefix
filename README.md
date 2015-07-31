# babel-plugin-react-autoprefix

Adds vendor prefixes to inline styles in React elements through
[autoprefix](https://github.com/uxtemple/autoprefix).

## Installation

```sh
$ npm install babel-plugin-react-autoprefix
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["react-autoprefix"]
}
```

### Via CLI

```sh
$ babel --plugins react-autoprefix script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["react-autoprefix"]
});
```

# TODO

- Work when styles are extracted into variables.
