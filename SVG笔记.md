---
title: SVG笔记
layout: category
permalink: /categories/SVG笔记/
taxonomy: SVG笔记
---

分类《SVG笔记》下的文章：
#SVG 意为可缩放矢量图形（Scalable Vector Graphics）。
#SVG 使用 XML 格式定义图像。
<!DOCTYPE html>
<html>
<body>
<h1>My first SVG</h1>
<svg xmlns="http://www.w3.org/2000/svg" version="1.1">
   <circle cx="100" cy="50" r="40" stroke="black" stroke-width="2" fill="red" />
</svg> 
</body>
</html>
##位图/点阵图或 光栅图 Bitmap or raster images
就是最小单位由像素构成的图，只有点的信息。缩放时会失真。每个像素有自己的颜色，
类似电脑里的图片都是像素图，把它放很大就会看到点变成小色块了。这种格式的图适合存储图形不规则，
而且颜色丰富没有规律的图，比如照相、扫描。 BMP,GIF,JPG等等.格式的文件。
##矢量图像 Vector images 
矢量图使用线条丶多边形丶点丶曲线和填充效果的数学描述来创建图像。
矢量图像通常是简单和图解形式的，像图(graphs)丶数据图(charts)和图解 (diagrams)，只能靠软件生成，
矢量图很少有光栅图(如照片)有深度或复杂度。但是矢量图和光栅图相比具有一些重要的优势: 
因为矢量图像文件只是形状的简略描述，所以文档小，下载快。 
矢量图像可以缩放到任何大小，而不减损其质量，和分辨率无关。 
虽然矢量图大多是图解式的，若配加以阴影和颜色，矢量图也可以变得非常写实。 
##可伸缩矢量图形 Scalable vector graphics—SVG 
svg 图像是W3C推出的基于XML的二维矢量图形标准，而不是像 Adobe Illustrator (.ai) 文件那样的产权专有的矢量图像格式。
大多数 .ai 图形可以保存在 svg 格式，进而直接用于网页上。作为矢量图， svg 图形可以缩放到任何大小，
而没有质量损失;由於其文档大小是紧凑的，因此在移动应用和响应网站创建图形方面， svg 越来越流行，至少对于相对简单的图像和形状来说。
##CSS 图形  CSS-based graphics 
层叠样式表 (css ) 的视觉样式功能长期以来拿来创建简单或复杂的图形效果，单靠 css 代码在网页上的使用。
最常见的 css 图形是图形按钮，纯 css 的技术拿來把简单的 html spans, divs, 及链接转换成任何颜色或形状的图形按钮，
可加配有阴影丶边缘丶阴影丶悬停和点击状态等效果。
css 技术能在网页上创建简单的图形效果，不需要內嵌 jpeg, gif, or png 图形，单靠 html 元素使用 css样式。
## 图标字体 Icon fonts 
图标字体 (icon fonts) 提供了一种简便方法，把数十甚至数百个矢量符号和图标，一次以非常紧凑的形式加载至网站中。
不同於一般计算机字体提供的是文字字母和数字字符 (alphanumeric characters) ，图标字体存的是各式图标，这样只需一次http 请求，网页就能有数以百计的矢量符号可用。
可以把一个 icon 看作是一个普通的文字，意味着直接用 css 控制文字属性，如 color、font-size，就可以改变图标的颜色和大小。
1111



