# Zeroway

Zeroway is a number formatter package.

### How to Install

Using npm
```shell
npm i zeroway
```

### Usage

Using require

```javascript
const zeroway = require('zeroway');

let number = 2500;
let digit = 2;

zeroway(number, digit);
```
Output: 2,5k

Using import

```javascript
import { numFormatter } from 'zeroway';

let number = 1500000;
let digit = 2;

numFormatter(number, digit);
```
Output: 1,5M
