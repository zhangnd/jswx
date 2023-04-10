# 微信JS-SDK

## 说明
微信js-sdk支持import导入

JS文件：https://res.wx.qq.com/open/js/jweixin-1.6.0.js

## 安装
```
npm i jswx
``` 

## 使用
vue
``` bash
import * as wx from 'jswx'
```

nuxt mounted
``` javascript
import('jswx').then(module => {
  const wx = module.default
})
```

## License
[MIT](LICENSE)