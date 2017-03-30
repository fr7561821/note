## CSS3选择器

### 属性选择器
- a[attr=value]选择到attr的值完全等于value的元素
- a[attr^=value]选择到attr的值以value开头的元素
- a[attr$=value]选择到attr的值以value结尾的元素
- a[attr*=value]选择的attr的值含有value的且在任意位置元素
- a[attr]选择到含有attr属性的元素

### 伪类选择器:

使用较多
- e:first-child 选择到的是e元素的父元素中的第一个子元素
- e:last-child 选择到的是e元素的父元素中的最后一个子元素
- e:nth-child(n)选择到的是e元素的父元素中的第n个子元素
- 小细节:数字 简单的表达式  特殊的关键字odd even
- n从0开始到无穷大
- 元素从1开始
- e:nth-last-child(n)选择到的是从后往前数第n个子元素

使用较少:
- e:empty 当某个元素中没有其他任何子元素或者没有文本内容的时候被选中
- e:target 选择到的是目标元素
- e:not(选择器) 选择到的是没有该选择器的元素

###伪元素选择器

使用多
- e::before
- e::after
功能:在元素的前后添加一个before和after这样两个伪元素

注意:1. 在使用伪元素的时候不要忘了content
2. 伪元素是行内元素
3. 伪元素添加给真实元素