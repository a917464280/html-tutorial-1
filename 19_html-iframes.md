# HTML 框架

--------

通过使用框架，你可以在同一个浏览器窗口中显示不止一个页面。

<iframe src="/html/" height="300px" width="99%"></iframe>

--------

**iframe语法:**

```HTML
<iframe src="<em>URL</em>"></iframe>
```

该URL指向不同的网页。

--------

## Iframe - 设置高度与宽度

height 和 width 属性用来定义iframe标签的高度与宽度。

属性默认以像素为单位, 但是你可以指定其按比例显示 (如："80%").

## 实例

```HTML
<iframe src="demo_iframe.htm" width="200" height="200"></iframe>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_iframe_height_width)

--------

## Iframe - 移除边框

frameborder 属性用于定义iframe表示是否显示边框。

设置属性值为 "0" 移除iframe的边框:

## 实例

```HTML
<iframe src="demo_iframe.htm" frameborder="0"></iframe>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_iframe_frameborder)

--------

## 使用iframe来显示目标链接页面

iframe可以显示一个目标链接的页面

目标链接的属性必须使用iframe的属性，如下实例:

## 实例

```HTML
<iframe src="demo_iframe.htm" name="iframe_a"></iframe>
<p><a href="http://www.runoob.com" target="iframe_a">RUNOOB.COM</a></p>
```

[尝试一下 »](http://www.runoob.com/try/try.php?filename=tryhtml_iframe_target)

--------

## HTML iframe 标签

| 标签 | 说明 |
| ---- | ---- |
| [&lt;iframe&gt;](http://www.runoob.com/tags/tag-iframe.html) | 定义一个内联的iframe |
