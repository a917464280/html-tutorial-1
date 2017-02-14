# HTML 链接

--------

HTML 使用超级链接与网络上的另一个文档相连。几乎可以在所有的网页中找到链接。点击链接可以从一张页面跳转到另一张页面。

--------

## ![Examples](images/tryitimg.gif) 尝试一下 - 实例

[HTML 链接](http://www.runoob.com/try/try.php?filename=tryhtml_links)

 如何在HTML文档中创建链接。

(可以在本页底端找到更多实例)

--------

## HTML 超链接（链接）

HTML使用标签 &lt;a&gt;来设置超文本链接。

超链接可以是一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档或者当前文档中的某个部分。

当您把鼠标指针移动到网页中的某个链接上时，箭头会变为一只小手。

在标签&lt;a&gt; 中使用了href属性来描述链接的地址。

默认情况下，链接将以以下形式出现在浏览器中：

 * 一个未访问过的链接显示为蓝色字体并带有下划线。
 * 访问过的链接显示为紫色并带有下划线。
 * 点击链接时，链接显示为红色并带有下划线。

> 注意：如果为这些超链接设置了 CSS 样式，展示样式会根据 CSS 的设定而显示。

--------

## HTML 链接语法

链接的 HTML 代码很简单。它类似这样：

```HTML
<a href="<i>url</i>"><i>链接文本</i></a>
```

href 属性描述了链接的目标。.

## 实例

```HTML
<a href="http://www.runoob.com/">访问菜鸟教程</a>
```

上面这行代码显示为：[访问菜鸟教程](http://www.runoob.com/)

点击这个超链接会把用户带到菜鸟教程的首页。

**提示:**  _"链接文本"_  不必一定是文本。图片或其他 HTML 元素都可以成为链接。

--------

## HTML 链接 - target 属性

使用 target 属性，你可以定义被链接的文档在何处显示。

下面的这行会在新窗口打开文档：

## 实例

```HTML
<a href="http://www.runoob.com/" target="_blank">访问菜鸟教程!</a>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_link_target)

--------

## HTML 链接- id 属性

id属性可用于创建在一个HTML文档书签标记。

**提示:**  书签是不以任何特殊的方式显示，在HTML文档中是不显示的，所以对于读者来说是隐藏的。

## 实例

在HTML文档中插入ID:

```HTML
<a id="tips">有用的提示部分</a>
```

在HTML文档中创建一个链接到"有用的提示部分(id="tips"）"：

```HTML
<a href="#tips">访问有用的提示部分</a>
```

或者，从另一个页面创建一个链接到"有用的提示部分(id="tips"）"：

```HTML
<a href="http://www.runoob.com/html/html-links.html#tips">

访问有用的提示部分</a>
```

--------

## 基本的注意事项 - 有用的提示

**注释：**  请始终将正斜杠添加到子文件夹。假如这样书写链接：href="http://www.runoob.com/html"，就会向服务器产生两次 HTTP 请求。这是因为服务器会添加正斜杠到这个地址，然后创建一个新的请求，就像这样：href="http://www.runoob.com/html/"。

--------

## ![Examples](images/tryitimg.gif) 更多实例

[图片链接](http://www.runoob.com/try/try.php?filename=tryhtml_imglink)

 如何使用图片链接。

[在当前页面链接到指定位置](http://www.runoob.com/try/try.php?filename=tryhtml_link_locations&basepath=0)

 如何使用书签

[跳出框架](http://www.runoob.com/try/try.php?filename=tryhtml_frame_getfree)

 本例演示如何跳出框架，假如你的页面被固定在框架之内。

[创建电子邮件链接](http://www.runoob.com/try/try.php?filename=tryhtml_mailto)

 本例演示如何链接到一个邮件。（本例在安装邮件客户端程序后才能工作。）

[建电子邮件链接 2](http://www.runoob.com/try/try.php?filename=tryhtml_mailto2)

 本例演示更加复杂的邮件链接。

--------

## HTML 链接标签

| 标签 | 描述 |
| ---- | ---- |
| [&lt;a&gt;](http://www.runoob.com/tags/tag-a.html) | 定义一个超级链接 |
