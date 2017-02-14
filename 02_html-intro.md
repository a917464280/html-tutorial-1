# HTML 简介

## HTML 实例

```HTML
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
</head>
<body>

<h1>我的第一个标题</h1>

<p>我的第一个段落。</p>

</body>
</html>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_intro)

## 实例解析

 * **&lt;!DOCTYPE html&gt;**  声明为 HTML5 文档
 * **&lt;html&gt;**  元素是 HTML 页面的根元素
 * **&lt;head&gt;**  元素包含了文档的元（meta）数据
 * **&lt;title&gt;**  元素描述了文档的标题
 * **&lt;body&gt;**  元素包含了可见的页面内容
 * **&lt;h1&gt;**  元素定义一个大标题
 * **&lt;p&gt;**  元素定义一个段落

--------

## 什么是HTML?

HTML 是用来描述网页的一种语言。

 * HTML 指的是超文本标记语言:  **H** yper **T** ext  **M** arkup  **L** anguage
 * HTML 不是一种编程语言，而是一种 **标记** 语言
 * 标记语言是一套 **标记标签**  (markup tag)
 * HTML 使用标记标签来 **描述** 网页
 * HTML 文档包含了HTML **标签** 及 **文本** 内容
 * HTML文档也叫做 **web 页面**

--------

## HTML 标签

HTML 标记标签通常被称为 HTML 标签 (HTML tag)。

 * HTML 标签是由 _尖括号_ 包围的关键词，比如 &lt;html&gt;
 * HTML 标签通常是 _成对出现_ 的，比如 &lt;b&gt; 和 &lt;/b&gt;
 * 标签对中的第一个标签是 _开始标签_ ，第二个标签是 _结束标签_
 * 开始和结束标签也被称为 _开放标签_ 和 _闭合标签_

&lt;标签&gt;内容&lt;/标签&gt;

--------

## HTML 元素

"HTML 标签" 和 "HTML 元素" 通常都是描述同样的意思.

但是严格来讲, 一个 HTML 元素包含了开始标签与结束标签，如下实例:

HTML 元素:

&lt;p&gt;这是一个段落。&lt;/p&gt;

--------

## Web 浏览器

Web浏览器（如谷歌浏览器，Internet Explorer，Firefox，Safari）是用于读取HTML文件，并将其作为网页显示。

浏览器并不是直接显示的HTML标签，但可以使用标签来决定如何展现HTML页面的内容给用户：

![](images/html-first.png)

--------

## HTML 网页结构

下面是一个可视化的HTML页面结构：

<div style="width:99%;border:1px solid grey;padding:3px;margin:0;background-color:#ddd">&lt;html&gt;
<div style="width:90%;border:1px solid grey;padding:3px;margin:20px">&lt;head&gt;
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;title&gt;页面标题&lt;/title&gt;
</div>
&lt;/head&gt;
</div>
<div style="width:90%;border:1px solid grey;padding:3px;margin:20px;background-color:#fff">&lt;body&gt;
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;h1&gt;这是一个标题&lt;/h1&gt;</div>
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;p&gt;这是一个段落。&lt;/p&gt;</div>
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;p&gt;这是另外一个段落。&lt;/p&gt;</div>
&lt;/body&gt;
</div>
&lt;/html&gt;
</div>

| ![Note](images/lamp.jpg) | 只有 &lt;body&gt; 区域 (白色部分) 才会在浏览器中显示。 |
| ---- | ---- |

--------

## HTML版本

从初期的网络诞生后，已经出现了许多HTML版本:

| 版本 | 发布时间 |
| ---- | ---- |
| HTML | 1991 |
| HTML+ | 1993 |
| HTML 2.0 | 1995 |
| HTML 3.2 | 1997 |
| HTML 4.01 | 1999 |
| XHTML 1.0 | 2000 |
| HTML5 | 2012 |
| XHTML5 | 2013 |

--------

## &lt;!DOCTYPE&gt; 声明

&lt;!DOCTYPE&gt;声明有助于浏览器中正确显示网页。

网络上有很多不同的文件，如果能够正确声明HTML的版本，浏览器就能正确显示网页内容。

doctype 声明是不区分大小写的，以下方式均可：

```HTML
<!DOCTYPE html>

<!DOCTYPE HTML>

<!doctype html>

<!Doctype Html>
```

--------

## 通用声明

### HTML5

```HTML
<!DOCTYPE html>
```

### HTML 4.01

```HTML
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
"http://www.w3.org/TR/html4/loose.dtd">
```

### XHTML 1.0

```HTML
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
```

查看完整网页声明类型 [DOCTYPE 参考手册](http://www.runoob.com/tags/tag-doctype.html)。

--------

## 中文编码

目前在大部分浏览器中，直接输出中文会出现中文乱码的情况，这时候我们就需要在头部将字符声明为 UTF-8。

## HTML 实例

```HTML
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>页面标题</title>
</head>
<body>

<h1>我的第一个标题</h1>

<p>我的第一个段落。</p>

</body>
</html>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_intro_utf8)
