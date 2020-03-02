# vue-pure-back
这是个测试项目，在头部加载了faceboock插件，在`public/index.html` `第八行`引入。
测试1：
① 点击首页的`about页`进入`about页`，此时`network`看到的`facebook插件`还在`pending状态`，
② 点击`about页`的返回，页面卡住，但是`url`已经变成`home页`
③ 等待`facebook` `pending状态`变化后，页面恢复；

测试2：
① 回到首页，刷新
② 重复测试1的步骤①
③ 点击点击链接到home页
④ 正常条状，没有卡住

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Run your unit tests
```
yarn run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
