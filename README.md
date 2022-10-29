# 项目基本介绍

## 1. 项目中使用的第三方库
### 1.1 npm i @craco/craco@alpha -D
```javascript
// create-react-app config 将craco.config.js合并到webpack中
  "scripts": {
    "start": "craco start",
    "build": "craco build",
    "test": "craco test",
    "eject": "react-scripts eject"
  },

```
### 1.2  npm i craco-less@2.1.0-alpha.0
```javascript
// craco-less@2.1.0-alpha.0 针对craco 7版本, 升级对应版本查看craco-less issues
const CracoLessPlugin = require('craco-less');
module.exports = {
  plugins: [
    {
      plugin: CracoLessPlugin
  ],
};
```

