jSelect
=======

实现自定义的select表单选择框控件：样式根据给定的css而表现，同时，保持select的onblure事件。

###控件简介###

一个jquery控件，实现自定义select样式的功能，同时保证select控件的交互功能。

###使用说明###

1.样式的自定义全部用css处理，位于css/jSelect.css，只需要修改相应的class名的属性就可以了。

2.此控件支持键盘操作，基本仿照原生的select控件的交互来开发。当改变控件当前的选择值的时候会自动触发原生select的blur事件，所以只需要用jQuery监听原生select的blur事件，就可以保证onblur事件的准确触发。

3.该控件的父元素 overflow属性不可设置为hidden




