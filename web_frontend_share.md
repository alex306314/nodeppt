title: Web前端开发基础知识分享
speaker: speaker
transition: cards
url: https://github.com/ksky521/nodePPT
headFiles:/js/jquery2.02.min.js
files: /js/demo.js,/css/demo.css
theme: light
<!--  colors-moon-blue-dark-green-light  -->

[slide]

# 前端基础知识分享
## 分享人：MeanOfWind

[slide]
#目录
----
<div class="mulu" style="text-align:left; width:320px;margin:0 auto;line-height:40px;">
  <h4><span class="num">一</span> 前端简介</h4>
  <h4><span class="num">二</span> 前端开发知识体系</h4>
  <h4><span class="num">三</span> 开发工具</h4>
  <h4><span class="num">四</span> 三要素</h4>
  <h4><span class="num">五</span> 进阶</h4>
  <h4><span class="num">六</span> 示例</h4>
</div>

[slide]
# 一、 前端简介

[slide]
<div class="section_title">前端简介</div>
# 1 什么是前端
---

* 我们这里所说的前端泛指WEB前端，也就是在WEB应用中用户可以看得见摸得着的东西

[slide]
<div class="section_title">前端简介</div>
# 2 前端的历史

* Web前端开发工程师是一个很新的职业，在国内乃至国际上真正开始受到重视的时间不超过5年。

* Web前端开发是从网页制作演变而来，名称上有很明显的时代特征。随着人们对用户体验的要求越来越高，前端开发的技术难度越来越大，Web前端开发这个职业也从设计和制作不分的局面中独立出来。

* 早期的前端其实就是Table布局，后来发展到DIV+CSS网站重构，再到JS逐渐成为web前端开发的语言及web2.0的出现，涌现出 相应的产品，如SNS、博客、微博等。人们对网页的需求不断增大，Web前端技术也在加速发展

[slide]
<div class="section_title">前端简介</div>
# 2 WEB前端开发现状

* 可用性、用户体验的关注度增强，“用户体验”团队的出现
<p class="list_des">如淘宝网的“淘宝UED”，百度旗下的“百度UFO”，腾讯的“ISD”和“CDC”等等</p>

* 职位划分
<p class="list_des">网页设计师，前端开发工程师，用户体验分析师，交互设计师等。主要集中于，设计，可用性，前端开发</p>


[slide]
# 二 前端开发知识体系

[slide]
<div class="section_title">前端开发知识体系</div>
# 1 前端开发-广义

<div class="guang clearfix">
  <img src="/images/allfrontend.jpg"/>
  <div class="gr">
    <p>从广义上来说，除了后台数据库应用开发外，前面的开发都可以叫做Web前端开发</p><br/>
    <p>前端工作包括4个部分<br/>
1.切图、IE兼容、CSS、HTML“传统”技术<br/>
2、Adobe AIR,<br/>
3、交互式设计<br/>
4、视觉设计</p>
  </div>
</div>


[slide]
<div class="section_title">前端开发知识体系</div>
# 2 前端开发核心(三要素)

<div class="guang clearfix">
  <img src="/images/htmlcss.jpg" style="width:300px;"/>
  <div class="gr" style="width:580px;">
    <p>web前端三层架构</p>
    <p style="font-size:18px;">1. 结构层（structural layer）</p>
    <p class="list_des" style="font-size:14px">由 HTML 或 XHTML之类的标记语言负责创建。标签，也就是那些出现在尖括号里的单词，对网页内容的语义含义做出了描述，但这些标签不包含任何关于如何显示有关内容的信息。例如，P标签表达了这样一种语义：“这是一个文本段。”</p>
    <p style="font-size:18px;">2. 表示层（presentation layer）</p>
    <p class="list_des" style="font-size:14px">由 CSS 负责创建。 CSS对“如何显示有关内容”的问题做出了回答。</p>
    <p style="font-size:18px;">3. 行为层（behaviorlayer）</p>
    <p class="list_des" style="font-size:14px">负责回答“内容应该如何对事件做出反应”这一问题。这是 Javascript 语言和 DOM主宰的领域</p>
  </div>
</div>

[slide]
# 三、开发工具

[slide]
<div class="section_title">开发工具</div>
----

* NotePad
* DreamWaver
* Sublime Text   [http://www.sublimetext.com/]
* Atom    [https://atom.io/]
* WebStorm
* PhpStorm


[slide]
# 四、三要素

[slide]
<div class="section_title">三要素之HTML</div>
# 1. 什么是 HTML？

<p class="al">HTML 是用来描述网页的一种语言。</p>

* HTML 指的是超文本标记语言 (Hyper Text Markup Language)
* HTML 不是一种编程语言，而是一种标记语言 (markup language)
* 标记语言是一套标记标签 (markup tag)
* HTML 使用标记标签来描述网页

[slide]
<div class="section_title">三要素之HTML</div>
# 2. HTML 标签

<p class="al">HTML 标记标签通常被称为 HTML 标签 (HTML tag)。</p>
* HTML 标签是由尖括号包围的关键词，比如 <html>
* HTML 标签通常是成对出现的，比如 <b> 和 </b>
* 标签对中的第一个标签是开始标签，第二个标签是结束标签
* 开始和结束标签也被称为开放标签和闭合标签

> [常用标签参考](http://w3school.com.cn/tags/index.asp)

[slide]
<div class="section_title">三要素之CSS</div>
# 1. CSS 概述

* CSS 指层叠样式表 (Cascading Style Sheets)
* 样式定义如何显示 HTML 元素
* 样式通常存储在样式表中
* 把样式添加到 HTML 4.0 中，是为了解决内容与表现分离的问题
* 外部样式表可以极大提高工作效率
* 外部样式表通常存储在 CSS 文件中
* 多个样式定义可层叠为一

[slide]
<div class="section_title">三要素之CSS</div>
# 2. CSS 选择器

|名称|示例|
|---|---|
|元素选择器|h1 {color:black;}|
|类选择器详解|.h1 {color:black;}|
|ID 选择器|#h1 {color:black;}|
|属性选择器|a[href] {color:black;}|
|后代选择器|div p {color:black;}|
|子元素选择器|div>p {color:black;}|
|相邻兄弟选择器|h4 + p {color:black;}|
|伪类|a:hover {color:black;}|
|伪元素|p:first-letter {color:black;}|


[slide]
<div class="section_title">三要素之CSS</div>
# 3. CSS 盒模型

<div class="guang clearfix">
  <img src="/images/cssbox.jpg" style="width:400px;"/>
  <div class="gr" style="width:480px;">
    <p class="list_des" style="font-size:18px">CSS 盒模型 (Box Model) 规定了元素框处理元素内容、内边距、边框 和 外边距 的方式。</p>
  </div>
</div>


[slide]
<div class="section_title">三要素之Javascript</div>
# 1. jQuery

<div class="cls" style="width:100px;height:30px;background:blue;margin-bottom:10px;"></div>
<script>
$('.cls').hover(function(){$(this).css({background:'red'})}, function(){$(this).css({background:'blue'})})
</script>

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="jquery.min.js"></script>
  </head>
  <body>
    <div class="cls"></div>
    <script type="text/javascript">
      $('.cls').hover(function(){
        $(this).css({background:'red'})
      }, function(){
          $(this).css({background:'blue'})
        })
    </script>
  </body>
</html>

```

[slide]
# 五、进阶

* JS高级：闭包、面向对象
* sass/less CSS语法扩展
* grunt/gulp自动化构建，webpack静态资源打包
* react/angular/reactNative模块化开发

[slide]
# 六、示例
----

```html
<div class="navw">
  <ul class="nav clearfix">
    <li><a>首页</a></li>
    <li>
      <a>产品展示</a>
      <ul class="subnav">
        <li><a>子菜单</a></li>
      </ul>
    </li>
    <li><a>关于我们</a></li>
  </ul>
</div>

```


<div class="navw">
<ul class="nav clearfix">
  <li><a>首页</a></li>
  <li><a>资讯</a></li>
  <li>
    <a>产品展示</a>
    <ul class="subnav">
      <li><a>子菜单</a></li>
      <li><a>子菜单</a></li>
      <li><a>子菜单</a></li>
      <li><a>子菜单</a></li>
    </ul>
  </li>
  <li>
    <a>荣誉资质</a>
    <ul class="subnav">
      <li><a>子菜单</a></li>
      <li><a>子菜单</a></li>
      <li><a>子菜单</a></li>
      <li><a>子菜单</a></li>
    </ul>
  </li>
  <li><a>关于我们</a></li>
</ul>
</div>



[slide]
## 谢谢
