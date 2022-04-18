## :maple_leaf: @wepy/plugin-minify
mini code plugin for Wepy

##### terser

##### pretty-data



* ### install
```
  npm install @wepy/plugin-minify -D
```

* ### setup
```javascript
const WepyPluginMinify = require('@wepy/plugin-minify');

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
