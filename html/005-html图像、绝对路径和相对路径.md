## html图像、绝对路径和相对路径

#### html图像

&lt;img&gt;标签可以在网页上插入一张图片，它是独立使用的标签，通过“src”属性定义图片的地址，通过“alt”属性定义图片加载失败时显示的文字，以及对搜索引擎和盲人读屏软件的支持。

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>图片</title>
</head>
    <body style="background-color:#d6dbdf">
        <img src="apple.png" alt="苹果">
    </body>
</html>
```

#### ![](/assets/10.png)

#### 绝对路径和相对路径

像网页上插入图片这种外部文件，需要定义文件的引用地址，引用外部文件还包括引用外部样式表，javascript等等，引用地址分为绝对地址和相对地址。

* 绝对地址：相对于磁盘的位置去定位文件的地址
* 相对地址：相对于引用文件本身去定位被引用的文件地址

**绝对地址在整体文件迁移时会因为磁盘和顶层目录的改变而找不到文件，相对路径就没有这个问题**。相对路径的定义技巧：

* **“ ./ ”** 表示当前文件所在目录下，比如：“./pic.jpg” 表示当前目录下的pic.jpg的图片，这个使用时可以省略。

* **“ ../ ”** 表示当前文件所在目录下的上一级目录，比如：“../images/pic.jpg” 表示当前目录下的上一级目录下的images文件夹中的pic.jpg的图片。

我的目录结构如下:

* html文件夹\(test.html,apple01.png\)
* images文件夹\(apple03.png\)
* apple02.png

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>相对路径</title>
</head>
<body>
    <!-- “./pic.jpg” 表示当前目录下的apple01.png的图片-->
    <img src="./apple01.png" alt="苹果01">
    <!-- “./pic.jpg” 表示当前目录下的apple01.png的图片，这个使用时可以省略-->
    <img src="apple01.png" alt="苹果01">
    <!--../images/pic.jpg” 表示当前目录下的上一级目录下apple02.png的图片-->
    <img src="../apple02.png" alt="苹果02">
    <!--“../images/pic.jpg” 表示当前目录下的上一级目录下的images文件夹中的apple03.png的图片。-->
    <img src="../images/apple03.png" alt="苹果03">
</body>
</html>
```

![](/assets/11.jpg)

