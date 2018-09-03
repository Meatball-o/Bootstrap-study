#### Bootstrap底层使用normalize.css对默认样式进行了重置。
## 起步
#### 按钮
```
<button type="button" class="btn btn-success btn-sm">（成功）Success</button>
  .btn .btn-default
  .btn-danger/warning/success/info/primary  按钮颜色
  .btn-lg/sm/xs			按钮大小
  .btn-block		块级按钮
```
#### 图片
```
  .img-rounded		    圆角图片
  .img-circle			圆形图片
  .img-thumbnail		缩略图片
  .img-responsive		响应式图片
```
#### 列表
```
  .list-unstyled		取消提示符
  .list-inline		行内列表
```
#### 辅助类
```
  .pull-left    左浮动
  .pull-right   右浮动
  .clearfix    清除浮动
  .caret        三角符号
  .close
```
#### 文本和排版
```
   h1 ~ h6
  .h1~.h6
  .text-danger/warning/success/info/primary  文本颜色
  .bg-danger/warning/success/info/primary    背景颜色

```
#### 表格
```
  .table
  .table-bordered		带边框的表格
  .table-striped		隔行变色的表格
  .table-hover			带鼠标悬停效果的表格
  .table-responsive		响应式表格，用于TABLE的父元素DIV上！
```
## 组件
#### 下拉菜单
```
下拉菜单必需的三级结构：
  <div class="dropdown">
    <a data-toggle="dropdown">触发元素</a>
    <ul class="dropdown-menu">隐藏元素</ul>
  </div>
```
#### 警告框
```
 <div class="alert alert-四种颜色 alert-dismissible">
	<span data-dismiss="alert"  class="close">×</span>
	警告消息
 </div>
```
#### 导航(nav)
##### 标签页式导航(nav-tabs)  胶囊式导航(nav-pills)
```
 <ul class="nav nav-tabs/pills">
	<li class="active"><a data-toggle="tab"></a></li>
	<li><a data-toggle="tab"></a></li>
 </ul>
```
#### 按钮组
```
 <div class="btn-group">
	<a class="btn"></a>
	.......
	<a class="btn"></a>
  </div>
```
#### 缩略图
```
  <a class="thumbnail"><img></a>

  <div class="thumbnail">
	<img>
	<div></div>
  </div>
```
#### 列表组
```
ul.list-group > li.list-group-item
div.list-group > a.list-group-item
```
#### 媒体对象
```
一个媒体对象(Media Object)用于介绍一个事物，分为“左中右”三部分，左右一般是图片，中部一般是说明文字
  <div class="media">
    <div class="media-left"></div>
    <div class="media-body"></div>
    <div class="media-right"></div>
  </div>
```
####  面板
```
 一个面板：就是框元素，分为“上中下”三级结构
  <div class="panel panel-五种颜色">
	<div class="panel-heading"></div>
	<div class="panel-body"></div>
	<div class="panel-footer"></div>
  </div>
```
#### 响应式导航条
```
<!--data-target="#aa"  与下边id="aa" id要对应-->

<nav class="nav navbar-default">
  <div class="navbar-header">
     <button type="button"
                class="navbar-toggle collapsed"
                data-toggle="collapse"
                data-target="#aa"
                aria-expanded="false">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
    <a href="#" class="navbar-brand">Brand</a>
  </div>
  <div class="collapse navbar-collapse" id="aa">
    <div class="nav navbar-nav">
        ...
    </div>
  </div>
</nav>
导航条的两种颜色：
	(1)浅色底深色的字： .navbar-default
	(2)深色底浅色的字： .navbar-inverse
导航条的两种定位：
	(1)相对定位（占用布局高度）： 默认
	(2)固定定位（不占用布局高度）： .navbar-fixed-*
导航条的两种位置：
	(1)页面顶部：相对定位  或者  .navbar-fixed-top
    (2)页面底部：.navbar-fixed-bottom
```
## 插件
#### Collapse（折叠效果）
```
  <a data-toggle="collapse" href="#xid"></a>
   <button data-toggle="collapse" data-target="#xid"></button>

  <div id="xid" class="collapse in">
	<div class="外观相关class">内容</div>
  </div>
```



