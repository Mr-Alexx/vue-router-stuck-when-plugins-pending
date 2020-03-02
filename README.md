# 头部加载了faceboock插件
在public/index.html第八行引入
## 测试1：  
  ① 点击首页的`about页`进入`about页`，此时`network`看到的`facebook插件`还在`pending状态`，  
  ② 点击`about页`的返回，页面卡住，但是`url`已经变成`home页`  
  ③ 等待`facebook` `pending状态`变化后，页面恢复；  

## 测试2：
  ① 回到首页，刷新  
  ② 重复测试1的步骤①  
  ③ 点击链接到`home页  `
  ④ 正常状态，没有卡住  

## 测试3：
作为比对，新增两个纯html页面，`pure-html目录`下  
  ① 打开`a.html`页面，点击`跳转到b页面`链接  
  ② `b.html`页面，点击返回  
  ③ 正常返回，不收插件影响  

## 附上代码：
[https://gitee.com/Mr-Alex/vue-router-stuck-when-plugins-pending](https://gitee.com/Mr-Alex/vue-router-stuck-when-plugins-pending)