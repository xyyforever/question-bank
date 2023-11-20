一、BFC概念
`BFC 即 Block Formatting Contexts (块级格式化上下文)，是W3C CSS2.1规范中的一个概念，决定了元素如何对其内容进行定位，以及与其他元素的关系和相互作用。具有BFC特性的元素可以看做是隔离了的独立容器，容器里面的元素不会在布局上影响到外面的元素，并且BFC具有普通容器所没有的的一些特性。`



触发BFC的几种方式
```
1、给元素设置浮动 float: left | right

2、给元素设置脱离文档流的定位 position: absolute | fixed

3、给元素设置内容溢出 overflow: hidden | scroll |auto

4、给元素设置 display: flex | inline-block | table-cell
```