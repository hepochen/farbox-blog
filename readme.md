status: not-post


## 文章属性的基本标注

	url: farbox-structure
	date: 2013-1-17 17:30
	title: FarBox.com的技术构架



## 文章额外的属性标注

	subtitle: 建筑
	cover:  /_image/2013-03-14/18-50-43.jpg
	cover_author: beggs
	intro:  匠者，唯心尔。这屋檐的边缘，未南飞的燕儿可以筑巢 .etc

其中，`subtitle`会在文章列表中，作为标题出现，`cover`为封面，如果未设定cover，则会取文章中的第一张图片作为封面。 `cover_author`为封面图的作者，鼠标放置于图片上，会显示做着。`intro`相当于文章列表中的摘要，如果没有设定，则会取文章正文的前面一部分作为摘要。


## site.md

如果你在site.md中写入`ga_id: xxxxxxx`，则会启用Google的统计代码，其中`xxxxx`是形如`UA-36651986-4`的id。


## 模板源码

托管于Github, [https://github.com/hepochen/farbox-blog](https://github.com/hepochen/farbox-blog)

