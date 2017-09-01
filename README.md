# ensureSymlink

used to implement a resilient "best-effort last write wins" symlink

## Usage

```sh
yarn add ensure-symlink

# or

npm install ensure-symlink
```

```js
const ensureSymlink = require('ensure-symlink');

ensureSymlink(from, to);
```
