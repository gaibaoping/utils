##### 这是我自己封装的一个简短的模仿jquery库中的一些方法的js库，下面对他的功能和用法进行简单的说明：
1. 可以共同JavaScript标签直接引用utils.js库；
2. utils库中的方法以utils对象的方式返回；
3. 方法主要有：
- listToArray : listToArray(likeAry),类数组转化成数组
- jsonParse : jsonParse(jsonStr),json字符串转化成json对象
- getRandom : getRandom(m,n),获取随机数
- offset : offset(ele),获取元素相对偏移量，返回一个对象{left: l, top: t}
- prev : prev(ele),获取元素的元素哥哥节点
- next  : next(ele),获取元素的元素弟弟节点
- children : children(ele, tagName),获取元素的指定子节点
- prevAll : prevAll(ele),获取元素所有的元素哥哥节点
- nextAll : nextAll(ele),获取元素所有的元素弟弟节点
- sibling : sibling(ele),获取元素相邻的元素兄弟节点
- siblings : siblings,获取元素所有的元素兄弟节点
- firstEleChild : firstEleChild(ele),获取元素的第一个元素子节点
- lastEleChild : lastEleChild(ele),获取元素的最后一个元素子节点
- hasClass : hasClass(ele,strClass),判断元素ele的class名是否是strClass
- addClass : addClass(ele, strClass),给元素ele添加class属性名
- removeClass : removeClass(ele, strClass),移除元素ele的class属性
- getElesByClass : getElesByClass(strClass,context),通过class属性获取元素，strClass可以是一个包含多个空格的字符串，context可有可无，可以限定要获取元素的区域范围。
- css : css(ele),其中包括getCss,setCss,setGroupCss,其中css的参数可以是(div,'attr',val) (div,'attr') (div,{})等几种形式。