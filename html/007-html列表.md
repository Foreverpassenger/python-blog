## html列表 {#html列表}

#### 有序列表 {#有序列表}

在网页上定义一个有编号的内容列表可以用&lt;ol&gt;、&lt;li&gt;配合使用来实现，代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>有序列表</title>
</head>
<body>
<ol>
    <li>列表文字一</li>
    <li>列表文字二</li>
    <li>列表文字三</li>
</ol>
</body>
</html>
```

![](/assets/15.png)

在网页上生成的列表，每条项目上会按1、2、3编号，有序列表在实际开发中较少使用。

#### 无序列表 {#无序列表}

在网页上定义一个无编号的内容列表可以用&lt;ul&gt;、&lt;li&gt;配合使用来实现，代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>无序列表</title>
</head>
<body>
<ul>
    <li>列表文字一</li>
    <li>列表文字二</li>
    <li>列表文字三</li>
</ul>
</body>
</html>
```

![](/assets/16.png)

在网页上生成的列表，每条项目上会有一个小图标，这个小图标在不同浏览器上显示效果不同，所以一般会用样式去掉默认的小图标，如果需要图标，可以用样式自定义图标，从而达到在不同浏览器上显示的效果相同,实际开发中一般用这种列表。

#### 定义列表 {#定义列表}

定义列表通常用于术语的定义。&lt;dl&gt;标签表示列表的整体。&lt;dt&gt;标签定义术语的题目。&lt;dd&gt;标签是术语的解释。一个&lt;dl&gt;中可以有多个题目和解释，代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>定义列表</title>
</head>
<body>
    <dl>        
        <dt>html</dt>
        <dd>负责页面的结构</dd>

        <dt>css</dt>
        <dd>负责页面的表现</dd>

        <dt>JavaScript</dt>
        <dd>负责页面的行为</dd>

    </dl>
</body>
</html>
```

#### ![](/assets/18.png)列表快捷键

在sublime创建列表快捷键：

```html
	<!-- ul>(li>a)*5   -->
	<ul>
		<li><a href="">新闻标题</a></li>
		<li><a href="">新闻标题</a></li>
		<li><a href="">新闻标题</a></li>
		<li><a href="">新闻标题</a></li>
		<li><a href="">新闻标题</a></li>
	</ul>
```



