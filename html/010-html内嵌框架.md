## html内嵌框架

#### html内嵌框架

&lt;iframe&gt;标签会创建包含另外一个html文件的内联框架（即行内框架），src属性来定义另一个html文件的引用地址，frameborder属性定义边框，scrolling属性定义是否有滚动条

#### 内嵌框架与a标签配合使用

a标签的target属性可以将链接到的页面直接显示在当前页面的iframe中，代码如下：

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>内嵌框架</title>
</head>
<body>
	<!--a标签的target属性可以将链接到的页面直接显示在当前页面的iframe中-->
	<a href="http://www.baidu.com" target="myframe">百度网</a>

	<a href="http://www.qq.com" target="myframe">腾讯网</a>

	<br>
	
	<iframe src="http://www.baidu.com" width="900" height="400" frameborder="0"  name="myframe">
	</iframe>
	<!--另一个html文件的引用地址-->
	<iframe src="022-html表单.html" width="900" height="400" frameborder="0" scrolling="no"></iframe>	

</body>
</html>
```



