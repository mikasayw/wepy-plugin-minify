## :maple_leaf: wepy-mini-plugin
mini code plugin for Wepy

##### terser

##### pretty-data



* ### install
```
  npm install wepy-mini-plugin -D
```

* ### setup
```javascript
const WepyMiniPlugin = require('wepy-mini-plugin');

module.exports = {
  plugins: [
    // 不传 options默认开启
    WepyMinifyPlugin({ enable: true })
  ],
};

```

* ## options
```javascript
default 
  options = {
    enabled: false,
    wxml: true,
    wxss: false,
    js: true,
    json: true,
    compress: {
      drop_console: true,
      drop_debugger: true
    },
  };
```
