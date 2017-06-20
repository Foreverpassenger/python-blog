## html段落、换行与字符实体

#### html段落

&lt;p&gt;标签定义一个文本段落，一个段落含有默认的上下间距，段落之间会用这种默认间距隔开，代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>段落</title>
</head>
<body>
    <p>HTML是 HyperText Mark-up Language 的首字母简写，意思是超文本标记语言，超
    文本指的是超链接，标记指的是标签，是一种用来制作网页的语言，这种语言由一个个的
    标签组成，用这种语言制作的文件保存的是一个文本文件，文件的扩展名为html或者htm。
    </p>

    <p>一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用文本的方
    式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件渲染成网页，显示的网
    页可以从一个网页链接跳转到另外一个网页。</p>
</body>
</html>
</body>
</html>
```

#### ![](/assets/3.png)

#### html换行

代码中成段的文字，直接在代码中回车换行，在渲染成网页时候不认这种换行，如果真想换行，可以在代码的段落中插入&lt;br /&gt;来强制换行，代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <p>
        一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用<br />
        文本的方式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件<br />
        渲染成网页，显示的网页可以从一个网页链接跳转到另外一个网页。
    </p>
</body>
</html>
```

#### html字符实体

代码中成段的文字，如果文字间想空多个空格，在代码中空多个空格，在渲染成网页时只会显示一个空格，如果想显示多个空格，可以使用空格的字符实体_**\( \)**,_代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    <!--  在段落前想缩进两个文字的空格，使用空格的字符实体：&nbsp;   -->
    <p>
        &nbsp;&nbsp;一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用<br />
        文本的方式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件<br />
        渲染成网页，显示的网页可以从一个网页链接跳转到另外一个网页。
    </p>
</body>
</html>
```

在网页上显示 “&lt;” 和 “&gt;” 会误认为是标签，想在网页上显示“&lt;”和“&gt;”可以使用它们的字符实体，比如：

```html

```



