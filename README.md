# size-transformer

文件大小单位转换

## 参数

- `size` {number} 要转换的文件大小 

## 用法

```js
const transformer = require('size-transformer');
console.log(transformer(1024 * 1024 * 1024 * 1024)); // 1.00 TB
console.log(transformer(1024)); // 1.00 KB
```
