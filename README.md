# common-utils

一个封装了 JS 的一些常用方法的工具

## 食用方法
git
1. 下载 npm 包

```shell
npm i common-utils
```

2. 使用 Validate 校验函数
```js
import { Validate } from 'common-utils'
const mobile = '17726366780'
Validate.mobileCheck(mobile) //true