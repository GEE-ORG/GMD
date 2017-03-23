# GMD - A new markdown parser

[![](https://img.shields.io/badge/npm-0.0.2-blue.svg)](https://www.npmjs.com/package/gmd-markdown-parser)


**still in alpha,not recommended for use in production environments**

## Usage

### Download GMD

```bash
yarn add gmd-markdown-parser --save
```

if you prefer npm

```bash
npm install gmd-markdown-parser --save
```

### Import and use GMD

```javascript
import GMD from 'gmd-markdown-parser';
const md = new GMD;

const html = md.parse('# H1 Title'); // <h1>H1 Title</h1>
```

## Support

- H1-H6
- separation
- em
- strong
- strikethrough
- ul/ol
- link
- image
- blockquote
- code
- pre

## Bugs already known

- code in pre tag still be parsed

## TODO

- diff