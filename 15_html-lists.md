# HTML 列表

--------

HTML 支持有序、无序和定义列表:

## HTML 列表

<div class="example_result notranslate">
<table width="100%" border="0">
<tbody><tr>
<td width="50%">
<h3>有序列表</h3>
<ol>
	<li>第一个列表项</li>
	<li>第二个列表项</li>
	<li>第三个列表项</li>
</ol>
</td>
<td width="50%">
<h3>无序列表</h3>
<ul>
	<li>列表项</li>
	<li>列表项</li>
	<li>列表项</li>
</ul>
</td>
</tr></tbody></table>
</div>

--------

##  ![实例](images/tryitimg.gif) 在线实例 

[无序列表](http://www.runoob.com/try/try.php?filename=tryhtml_lists4)

 本例演示无序列表。

[有序列表](http://www.runoob.com/try/try.php?filename=tryhtml_lists)

 本例演示有序列表。

（可以在本页底端找到更多实例。）

--------

## HTML无序列表

无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记。

无序列表使用 &lt;ul&gt; 标签

```HTML
<ul>
<li>Coffee</li>
<li>Milk</li>
</ul>
```

浏览器显示如下：

 * Coffee
 * Milk

--------

## HTML 有序列表

同样，有序列表也是一列项目，列表项目使用数字进行标记。 有序列表始于 &lt;ol&gt; 标签。每个列表项始于 &lt;li&gt; 标签。

列表项项使用数字来标记。

```HTML
<ol>
<li>Coffee</li>
<li>Milk</li>
</ol>
```

浏览器中显示如下：

2. Coffee

4. Milk

--------

## HTML 自定义列表

自定义列表不仅仅是一列项目，而是项目及其注释的组合。

自定义列表以 &lt;dl&gt; 标签开始。每个自定义列表项以 &lt;dt&gt; 开始。每个自定义列表项的定义以 &lt;dd&gt; 开始。

```HTML
<dl>
<dt>Coffee</dt>
<dd>- black hot drink</dd>
<dt>Milk</dt>
<dd>- white cold drink</dd>
</dl>
```

浏览器显示如下：

Coffee
- black hot drink
Milk
- white cold drink

--------

## 注意事项 - 有用提示

**提示:**  列表项内部可以使用段落、换行符、图片、链接以及其他列表等等。

--------

## [Examples](images/tryitimg.gif) 更多实例

[不同类型的有序列表](http://www.runoob.com/try/try.php?filename=tryhtml_lists_ordered)

 本例演示不同类型的有序列表。

[不同类型的无序列表](http://www.runoob.com/try/try.php?filename=tryhtml_lists_unordered)

 本例演示不同类型的无序列表。

[嵌套列表](http://www.runoob.com/try/try.php?filename=tryhtml_lists2)

 本例演示如何嵌套列表。

[嵌套列表 2](http://www.runoob.com/try/try.php?filename=tryhtml_nestedlists2)

 本例演示更复杂的嵌套列表。

[自定义列表](http://www.runoob.com/try/try.php?filename=tryhtml_lists3)

 本例演示一个定义列表。

--------

## HTML 列表标签

| 标签 | 描述 |
| ---- | ---- |
| [&lt;ol&gt;](http://www.runoob.com/tags/tag-ol.html) | 定义有序列表 |
| [&lt;ul&gt;](http://www.runoob.com/tags/tag-ul.html) | 定义无序列表 |
| [&lt;li&gt;](http://www.runoob.com/tags/tag-li.html) | 定义列表项 |
| [&lt;dl&gt;](http://www.runoob.com/tags/tag-dl.html) | 定义定义列表 |
| [&lt;dt&gt;](http://www.runoob.com/tags/tag-dt.html) | 自定义列表项目 |
| [&lt;dd&gt;](http://www.runoob.com/tags/tag-dd.html) | 定义自定列表项的描述 |
