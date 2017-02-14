# HTML 表单和输入

--------

HTML 表单用于搜集不同类型的用户输入。

--------

## ![Examples](images/tryitimg.gif) 在线实例

[创建文本字段 (Text field)](http://www.runoob.com/try/try.php?filename=tryhtml_input)

 本例演示如何在 HTML 页面创建文本域。用户可以在文本域中写入文本。

[创建密码字段](http://www.runoob.com/try/try.php?filename=tryhtml_inputpassword)

 本例演示如何创建 HTML 的密码域。

（在本页底端可以找到更多实例。）

--------

## HTML 表单

表单是一个包含表单元素的区域。

表单元素是允许用户在表单中输入内容,比如：文本域(textarea)、下拉列表、单选框(radio-buttons)、复选框(checkboxes)等等。

表单使用表单标签 &lt;form&gt; 来设置:

```HTML
<form>
.
<i>input 元素</i>
.
</form>
```

--------

## HTML 表单 - 输入元素

多数情况下被用到的表单标签是输入标签（&lt;input&gt;）。

输入类型是由类型属性（type）定义的。大多数经常被用到的输入类型如下：

--------

## 文本域（Text Fields）

文本域通过&lt;input type="text"&gt; 标签来设定，当用户要在表单中键入字母、数字等内容时，就会用到文本域。

```HTML
<form>
First name:
<input type="text" name="firstname">
Last name:
<input type="text" name="lastname">
</form>
```

浏览器显示如下：

<form action="">
First name: <input type="text" name="firstname" size="20"><br>
Last name: <input type="text" name="lastname" size="20">
</form>

**注意:** 表单本身并不可见。同时，在大多数浏览器中，文本域的缺省宽度是20个字符。

--------

## 密码字段

密码字段通过标签&lt;input type="password"&gt; 来定义:

```HTML
<form>
Password:
<input type="password" name="pwd">
</form>
```

浏览器显示效果如下:

<form action="">
Password: <input type="password" name="pwd">
</form>

**注意:** 密码字段字符不会明文显示，而是以星号或圆点替代。

--------

## 单选按钮（Radio Buttons）

&lt;input type="radio"&gt; 标签定义了表单单选框选项

```HTML
<form>
<input type="radio" name="sex" value="male">Male
<input type="radio" name="sex" value="female">Female
</form>
```

浏览器显示效果如下:

<form action="">
<input type="radio" name="sex" value="male">Male<br>
<input type="radio" name="sex" value="female">Female
</form>

--------

## 复选框（Checkboxes）

&lt;input type="checkbox"&gt; 定义了复选框. 用户需要从若干给定的选择中选取一个或若干选项。

```HTML
<form>
<input type="checkbox" name="vehicle" value="Bike">I have a bike
<input type="checkbox" name="vehicle" value="Car">I have a car 
</form>
```

浏览器显示效果如下:

<form action="">
<input type="checkbox" name="vehicle" value="Bike">I have a bike<br>
<input type="checkbox" name="vehicle" value="Car">I have a car 
</form>

--------

## 提交按钮(Submit Button)

&lt;input type="submit"&gt; 定义了提交按钮.

当用户单击确认按钮时，表单的内容会被传送到另一个文件。表单的动作属性定义了目的文件的文件名。由动作属性定义的这个文件通常会对接收到的输入数据进行相关的处理。:

```HTML
<form name="input" action="html_form_action.php" method="get">
Username:
<input type="text" name="user">
<input type="submit" value="Submit">
</form>
```

浏览器显示效果如下:

<form name="input0" target="_blank" action="/try/demo_source/html_form_action.php" method="get">
Username: <input type="text" name="user" size="20"><input type="submit" value="Submit">
</form>

假如您在上面的文本框内键入几个字母，然后点击确认按钮，那么输入数据会传送到 "html_form_action.php" 的页面。该页面将显示出输入的结果。

--------

## ![Try it](images/tryitpic.gif) 更多实例

[单选按钮(Radio buttons)](http://www.runoob.com/try/try.php?filename=tryhtml_radio)

 本例演示如何在 HTML 中创建单选按钮。

[复选框(Checkboxes)](http://www.runoob.com/try/try.php?filename=tryhtml_checkbox)

 本例演示如何在 HTML 页中创建复选框。用户可以选中或取消选取复选框。

[简单的下拉列表](http://www.runoob.com/try/try.php?filename=tryhtml_select2)

 本例演示如何在 HTML 页面中创建简单的下拉列表框。下拉列表框是一个可选列表。

[预选下拉列表](http://www.runoob.com/try/try.php?filename=tryhtml_select3)

 本例演示如何创建一个简单的带有预选值的下拉列表。

[文本域(Textarea)](http://www.runoob.com/try/try.php?filename=tryhtml_textarea)

 本例演示如何创建文本域（多行文本输入控件）。用户可在文本域中写入文本。可写入字符的字数不受限制。

[创建按钮](http://www.runoob.com/try/try.php?filename=tryhtml_button)

 本例演示如何创建按钮。你可以对按钮上的文字进行自定义。

## ![Try it](images/tryitpic.gif) 表单实例

[带边框的表单](http://www.runoob.com/try/try.php?filename=tryhtml_legend)

 本例演示如何在数据周围绘制一个带标题的框。

[带有输入框和确认按钮的表单](http://www.runoob.com/try/try.php?filename=tryhtml_form_submit)

 本例演示如何向页面添加表单。此表单包含两个输入框和一个确认按钮。

[带有复选框的表单](http://www.runoob.com/try/try.php?filename=tryhtml_form_checkbox)

 此表单包含两个复选框和一个确认按钮。

[带有单选按钮的表单](http://www.runoob.com/try/try.php?filename=tryhtml_form_radio)

 此表单包含两个单选框和一个确认按钮。

[从表单发送电子邮件](http://www.runoob.com/try/try.php?filename=tryhtml_form_mail)

 此例演示如何从表单发送电子邮件。

--------

## HTML 表单标签

New&nbsp;: HTML5新标签

| 标签 | 描述 |
| ---- | ---- |
| [&lt;form&gt;](http://www.runoob.com/tags/tag-form.html) | 定义供用户输入的表单 |
| [&lt;input&gt;](http://www.runoob.com/tags/tag-input.html) | 定义输入域 |
| [&lt;textarea&gt;](http://www.runoob.com/tags/tag-textarea.html) | 定义文本域 (一个多行的输入控件) |
| [&lt;label&gt;](http://www.runoob.com/tags/tag-label.html) | 定义了 &lt;input&gt; 元素的标签，一般为输入标题 |
| [&lt;fieldset&gt;](http://www.runoob.com/tags/tag-fieldset.html) | 定义了一组相关的表单元素，并使用外框包含起来 |
| [&lt;legend&gt;](http://www.runoob.com/tags/tag-legend.html) | 定义了 &lt;fieldset&gt; 元素的标题 |
| [&lt;select&gt;](http://www.runoob.com/tags/tag-select.html) | 定义了下拉选项列表 |
| [&lt;optgroup&gt;](http://www.runoob.com/tags/tag-optgroup.html) | 定义选项组 |
| [&lt;option&gt;](http://www.runoob.com/tags/tag-option.html) | 定义下拉列表中的选项 |
| [&lt;button&gt;](http://www.runoob.com/tags/tag-button.html) | 定义一个点击按钮 |
| [&lt;datalist&gt;](http://www.runoob.com/tags/tag-datalist.html)New | 指定一个预先定义的输入控件选项列表 |
| [&lt;keygen&gt;](http://www.runoob.com/tags/tag-keygen.html)New | 定义了表单的密钥对生成器字段 |
| [&lt;output&gt;](http://www.runoob.com/tags/tag-output.html)New | 定义一个计算结果 |
