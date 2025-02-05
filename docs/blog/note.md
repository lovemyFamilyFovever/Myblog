---
outline: [0,3]
layout: doc
---

- 样式或者资源文件加载不成功，原因是由于 base 路径配置错误。修改 `config.mjs` 文件中的 base 属性为 `/` 即可。

```js
const base = '/';
```

