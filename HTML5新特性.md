## 1.什么是HTML5
### 狭义上的HTML5
1. HTML4.0的升级版
2. HTML5+CSS3+新增JS api的技术组合

### 广义上的HTML5
1.HTML5行业的代名词
2.当前新技术的代名词

### 语法规范
```javascript
<!DOCTYPE html>
<html lang="en">
<meta charset="UTF-8">
```

## 2.HTML5标签语义化
### 看见改标签就知道大概的内容
1. 便于搜索引擎搜索
2. 便于开发人员维护
3. 便于残障人士更好的获取互联网信息。

### 常用标签
- header
- nav
- main
- aside
- seciton 内容
- footer
- article 博客中用的多一些
- mark 标记。黄色背景色
- progress 进度条  有最大，最小值

## 3.HTML5表单


## 只有自己才能看明白的总结
1. HTML5标签书写规范   ！DOCTYPE html、html lang=en 、  meta  charset=utf-8
2. 标签语义化。好处：1.搜索引擎  2.维护  3.盲人
3. 新增标签    ie8 不兼容，引入 html5shiv.js  、  cc:ie6  
4. form表单输入类型：search 、tel、 email 、date 、time、color、range、 url 、   datalist， id和 input  list属性一样，获取option的value
5. form属性 placeholder  、 autofocus  、 autocomplete=on/off  、  required pattern、   multipel
6. HTML5 媒体标签：audio、  video，  属性：controls控制器 、  autoplay 、  loop 循环  
7. DOM扩展  
获取元素的新API ：  document.querySelector/All
8. 类名操作：   node.classList.add()  、  node.classList.remove()、  node.classList.toggle()
  node.classList.contains() 判断时候包含某个属性，
9. 自定义属性：  data-*  、 data-*-*  、  获取值：  node.dataset.xxxx  、  node.dataset获取全部的自定义属性，是一个对象。  node.dataset.xxxx = xxxx 设置自定义属性