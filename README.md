# size-transformer

文件大小单位转换

## install

```bash
npm i @lxfriday/size-transformer
// or
yarn add @lxfriday/size-transformer
```

## 参数

- `size` {number} 要转换的文件大小 

## 用法

```js
const transformer = require('@lxfriday/size-transformer');
console.log(transformer(1024 * 1024 * 1024 * 1024)); // 1.00 TB
console.log(transformer(1024)); // 1.00 KB
```
