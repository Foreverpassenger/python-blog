## html链接

#### html链接

&lt;a&gt;标签可以在网页上定义一个链接地址，通过src属性定义跳转的地址，通过title属性定义鼠标悬停时弹出的提示文字框。

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>链接</title>
</head>
<body style="background-color:#d6dbdf">
    <a href="http://www.baidu.com" title="跳转到百度的网站">传智播客</a>
    <a href="http://www.baidu.com" title="跳转到百度的网站">
        <img src="apple.png" alt="百度logo">
    </a>

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />



    <!-- 链接到页面顶部   -->

    <a href="#">新闻标题</a>

    <!-- 不做任何操作   -->
    <a href="javascript:;">缺省值</a>

</body>
</html>
```

#### ![](/assets/12.gif)

#### 定义页面内滚动跳转

页面内定义了“id”的元素，可以通过a标签链接到它的页面滚动位置，前提是页面要足够高，有滚动条，且元素不能在页面顶部，否则页面不会滚动。

1.底部如果没有内容

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>页面内跳转</title>
</head>
<body style="background-color:#d6dbdf">
    <h1 id="biaoti01">标题一</h1>
    <a href="#biaoti01">标题一</a>
    <a href="#biaoti02">标题二</a>

    <p>HTML是 HyperText Mark-up Language 的首字母简写，意思是超文本标记语言，超文本指的是超链接，标记指的是标签，是一种用来制作网页的语言，这种语言由一个个的标签组成，用这种语言制作的文件保存的是一个文本文件，文件的扩展名为html或者htm，一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用文本的方式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件渲染成网页，显示的网页可以从一个网页链接跳转到另外一个网页。</p>

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />



    <h1 id="biaoti02">标题二</h1>
    <a href="#biaoti01">标题一</a>
    <a href="#biaoti02">标题二</a>
    <p>HTML是 HyperText Mark-up Language 的首字母简写，意思是超文本标记语言，超文本指的是超链接，标记指的是标签，是一种用来制作网页的语言，这种语言由一个个的标签组成，用这种语言制作的文件保存的是一个文本文件，文件的扩展名为html或者htm，一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用文本的方式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件渲染成网页，显示的网页可以从一个网页链接跳转到另外一个网页。</p>
    <!-- 跳转的底部如果没有内容-->

</body>
</html>
```

![](/assets/13-1.gif)

2.底部如果有内容且足够长

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>页面内跳转</title>
</head>
<body style="background-color:#d6dbdf">
    <h1 id="biaoti01">标题一</h1>
    <a href="#biaoti01">标题一</a>
    <a href="#biaoti02">标题二</a>

    <p>HTML是 HyperText Mark-up Language 的首字母简写，意思是超文本标记语言，超文本指的是超链接，标记指的是标签，是一种用来制作网页的语言，这种语言由一个个的标签组成，用这种语言制作的文件保存的是一个文本文件，文件的扩展名为html或者htm，一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用文本的方式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件渲染成网页，显示的网页可以从一个网页链接跳转到另外一个网页。</p>

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />

    <br />
    <br />
    <br />
    <br />
    <br />
    <br />



    <h1 id="biaoti02">标题二</h1>
    <a href="#biaoti01">标题一</a>
    <a href="#biaoti02">标题二</a>
    <p>HTML是 HyperText Mark-up Language 的首字母简写，意思是超文本标记语言，超文本指的是超链接，标记指的是标签，是一种用来制作网页的语言，这种语言由一个个的标签组成，用这种语言制作的文件保存的是一个文本文件，文件的扩展名为html或者htm，一个html文件就是一个网页，html文件用编辑器打开显示的是文本，可以用文本的方式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件渲染成网页，显示的网页可以从一个网页链接跳转到另外一个网页。</p>
    <!-- 跳转的底部如果有内容且足够长-->
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
</body>
</html>
```

![](/assets/13-3.gif)

#### 打开新窗口跳转

&lt;a&gt; 标签的 target 属性规定在何处打开链接文档。

如果在一个 &lt;a&gt; 标签内包含一个 target 属性，浏览器将会载入和显示用这个标签的 href 属性命名的、名称与这个目标吻合的框架或者窗口中的文档。如果这个指定名称或 id 的框架或者窗口不存在，浏览器将打开一个新的窗口，给这个窗口一个指定的标记，然后将新的文档载入那个窗口。从此以后，超链接文档就可以指向这个新的窗口。

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>定义链接跳转目标窗口</title>
</head>
<body>
	<a href="http://www.baidu.com" title="链接到百度" target="_blank">百度网</a>
</body>
</html>
```

![](/assets/14-1.gif)

