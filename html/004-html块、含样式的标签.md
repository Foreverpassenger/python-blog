## html块、含样式的标签

---

#### html块

1、div标签 块元素，表示一块内容，没有具体的语义。  
2、span标签 行内元素，表示一行中的一小段内容，没有具体的语义。

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>html块</title>
    <style type="text/css">
        body{
            background-color: #d6dbdf
        }
    </style>
</head>
<body>
    <div>1232</div>
    <span>1232</span>
    <div>
        一个html文件就是一个<span>网页</span>，html文件用编辑器打开显示的是文本，可以用文本的方
           式编辑它，如果用浏览器打开，浏览器会按照标签描述内容将文件渲染成网页，显示的网
        页可以从一个网页链接跳转到另外一个网页    
    </div>
</body>
</html>
```

#### ![](/assets/7.png)

---

#### 含样式和语义的标签

1、em标签 行内元素，表示语气中的强调词  
2、i标签 行内元素，原本没有语义，w3c强加了语义，表示专业词汇  
3、b标签 行内元素，原本没有语义，w3c强加了语义，表示文档中的关键字或者产品名  
4、strong标签 行内元素，表示非常重要的内容

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body style="background-color:#d6dbdf">
    <p>
        一个<em>html</em>文件就是一个网页
    </p>
    <p>
        一个html<i>文件</i>就是一个网页
    </p>
    <p>
        一个html文件就是<b>一个</b>网页
    </p>
    <p>
        一个html文件就是一个<strong>网页</strong>
    </p>

</body>
</html>
```

#### ![](/assets/8.png)

---

#### 语义化的标签

语义化的标签，就是在布局的时候多使用语义化的标签，搜索引擎在爬网的时候能认识这些标签，理解文档的结构，方便网站的收录。比如：h1标签是表示标题，p标签是表示段落，ul、li标签是表示列表，a标签表示链接，dl、dt、dd表示定义列表等，语义化的标签不多。

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
    <body style="background-color:#d6dbdf">
    <h1>标题</h1>
    <p>段落</p>
    <ul>
        <li>列表</li>
        <li>列表</li>
        <li>列表</li>
    </ul>
    <a href="www.baidu.com">链接</a>
    <dl>
        <dt>列表</dt>
        <dd>列表</dd>
        <dt>列表</dt>
        <dd>列表</dd>
    </dl>
</body>
</html>
```

![](/assets/9.png)

