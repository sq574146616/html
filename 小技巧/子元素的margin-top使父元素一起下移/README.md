父元素的盒子包含一个子元素盒子，给子元素盒子一个垂直外边距margin-top,父元素盒子也会往下走margin-top的值，而子元素和父元素的边距则没有发生变化。

解决方法：
1、修改父元素的高度，增加padding-top样式模拟（padding-top：1px；常用）
2、为父元素添加overflow：hidden；样式即可（完美）
3、为父元素或者子元素声明浮动（float：left；可用）
4、为父元素添加border（border:1px solid transparent可用）
5、为父元素或者子元素声明绝对定位
