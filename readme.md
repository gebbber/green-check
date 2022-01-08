# Green Checkmark v1.0.0

Allows you to use a green checkmark in the console!!

## With '`require`':
```javascript
const greenCheckmark = require('../index.js');

console.log('Works from a CommonJs file', greenCheckmark);
```

## With '`import`' from a Module:
```javascript
const greenCheckmark = (await import('../index.js')).default;

console.log('Works from a module', greenCheckmark);
```