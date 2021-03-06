# 第二天：给自己做一个在线简历吧

* [1 任务描述](#1)
    * [一份自己的在线简历(虚拟数据即可)](https://zerokitsune.github.io/d2/index.html)
        - 简历页面肯定要有的“简历”两个字
        - 简历的“姓名：van”，“性别♂” 之类的啊
        - 联系方式，QQ，Facebook(滑稽)，陌陌？
        - 学历，霍格沃茨魔法学校格兰芬多学院普通巫师
        - 项目经验，唔，这不正学习呢么（最后成为一名超级巫师）

* [2 课程目标](#2)
    * [2.1 html是什么](#2.1)
    	* [2.1.1 html5是什么](#2.1)
    * [2.2 基本的html标签](#2.2)
    * [2.3 文档类型](#2.3)
    * [2.4 meta标签](#2.4)
    * [2.5 Web语义化](#2.5)
    * [2.6 链接](#2.6)
    * [2.7 表单](#2.7)
    * [2.8 列表](#2.8)
* [引用资料](#3)




<h2 id="2.1">关于html和html5</h2>

- html(常指HTML4.01)
	> HTML，超文本标记语言，“超文本”就是指页面内可以包含图片、链接，甚至音乐、程序等非文字元素。 ---百度百科

	__就是描述网页的语言，有以下特性__

	+ HTML 使用标记标签来描述网页
	+ HTML 标签是由尖括号包围的关键词，比如 ` <html><i><p> `
	+ HTML 文档也被称为网页
	+ ...
- html 5
	> 超文本标记语言（HTML）的第五次重大修改。 ---百度百科
	
	__下一句话划重点！__

	__html5不是一个单独的语言是继html，所以不存在“请给我做一个酷炫的html5 app”这个选项，最起码也是“标准为html5的app”__ 

***

<h2 id="2.2">html标签</h2>

- 标签
	> 超文本标记语言（HTML）标记标签通常被称为HTML标签，HTML标签是HTML语言中最基本的单位，HTML标签是HTML（标准通用标记语言下的一个应用）最重要的组成部分。
	
	__html标签是组成网页的部分，也是超级超级超级重要的部分,如，` <header></header> ` (人体结构这样，你懂我的意思吧)__
- 标签属性
	> HTML标签可以拥有属性。属性提供了有关 HTML 元素的更多的信息。 ---www.w3school.com.cn
	
	__属性，` color:green ` ，表现在网页的效果就是绿色的字(绿色的头发，你懂我的意思吧(滑稽))__

***

<h2 id="2.3">文档类型</h2>

- <!DOCTYPE> 声明
	> Web 世界中存在许多不同的文档。只有了解文档的类型，浏览器才能正确地显示文档。

	> HTML 也有多个不同的版本，只有完全明白页面中使用的确切 HTML 版本，浏览器才能完全正确地显示出 HTML 页面。这就是 <!DOCTYPE> 的用处。

	> <!DOCTYPE> 不是 HTML 标签。它为浏览器提供一项信息（声明），即 HTML 是用什么版本编写的。 ---www.w3school.com.cn

	__告诉你的浏览器，你写的这个网页要拿什么东西看__
	__ 现在网页一开始写个 ` <!DOCTYPE html> ` 就ok了__



***

<h2 id="2.4">meta标签</h2>

- meta标签
	> <meta> 元素可提供有关页面的元信息（meta-information），比如针对搜索引擎和更新频度的描述和关键词。

	> <meta> 标签永远位于文档的头部，不包含任何内容。<meta> 标签的属性定义了与文档相关联的名称/值对。 ---www.w3school.com.cn
	
	__ ` <meta charset="utf-8"> ` 很常见的一个标签，用来规定当前html文档(网页)的字符编码(gb2312了解一下？就是没了这些东西，就乱码了 ` @\珪愮檌&郪?肮膊2n?4>錖?繻& ` )__

	__初期不会太用到，大概了解下就好__

***

<h2 id="2.5">Web语义化</h2>

- 语义化
	> 语义化是指用合理HTML标记以及其特有的属性去格式化文档内容。通俗地讲,语义化就是对数据和信息进行处理,使得机器可以理解。 ---百度百科

	__个人感觉，就是更加清楚明了 ` <div class="header"></div> ` 和 ` <header></header> ` 应该一下就可以看出看来，后面的更加简单方便(无论是人还是机器)(还是人体结构，“一个叫头部的物体”和“头部”，应该一眼明了)__
	
	__个人读起来更舒服，代码也更整洁；对机器来说，更容易处理，不用考虑没用的信息__

***

<h2 id="2.6">链接</h2>

- 链接
	+ 就是那种暗红色背景的房间，然后一个男的一个女的，女的被绑在那里还带着链。。链接，唔，咳咳，这是手铐
	+ 1对1，你叫大卫，我叫了一声“大卫”。这个时候就形成了个链接。
	+ html中，链接的表现形式有几种(不确定其中的几种算不算)
		* ` <a href="https://www.baidu.com/">嘿嘿嘿</a> ` ，这就是一个明面写着“嘿嘿嘿”，点开确实百度首页的 __超链接__ 黑车
		* ` <link rel="stylesheet" href="style.css"> ` ，唔，这是一种 __引用__ 样式表的方法
		* ` <img src="av.png" alt=""> ` 这个，猜猜是啥意思

***

<h2 id="2.7">表单标签 ` <form> ` </h2>

- form
	+ "请输入您的账号"，"点击同意继续"，眼不眼熟
	+ __我理解的表单，就是用来提交数据的，有输入账号的，有输入密码的，还有提交和忘记密码这些功能的__

***

<h2 id="2.8">列表</h2>

- 列表
	+ ul
	+ ol
	+ dl

- ul(Unordered List 无序列表),li(lists/list item 目录，清单/列表单元)
	__以下将是一个无序列表带着两个列表单元的例子__
	+ 动漫的分类
		* 色情的里番
		* 不色情的里番

- ol(Ordered List有序列表),li
	__还是个例子__
	+ bilibili的分区
		1. 鬼畜区
		2. 素材区

- dl(Definition List 定义列表),dt(define list title),dd(define list define)
	__惯例，dl带着dt，dd描述dt__
	+ 兄贵
		日文：あにき
		日文罗马字：A ni ki
		文学：哲学
	__这个不像上面两个列表有明显的层次关系，这个主要是“解释”，解释“兄贵”这个词汇__

***

<h2 id="3">引用资料</h2>

- [文档类型](http://www.w3school.com.cn/html/html_doctype.asp)
- [html是啥](http://www.w3school.com.cn/html/html_jianjie.asp)
- [html5又是啥](http://www.w3school.com.cn/html5/index.asp)
- [meta标签](http://www.w3school.com.cn/tags/tag_meta.asp)