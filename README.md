# @beyond-js/code

Simple utility functions for code manipulation.

## Installation

```bash
npm install @beyond-js/code
```

## Usage

```javascript
const { header, scoped } = require('@beyond-js/code');

// Create a header for a file
const fileHeader = header('My JavaScript File');
console.log(fileHeader);

// Wrap code in a scoped IIFE
const myCode = `
const x = 1;
console.log(x);
`;
const scopedCode = scoped(myCode);
console.log(scopedCode);
```

## API

-   `header(text: string): string` - Creates a comment header for code files.
-   `scoped(code: string): string` - Wraps code in a scoped IIFE and adds indentation.

## License

MIT © [[BeyondJS](https://beyondjs)]
