---
{"dg-publish":true,"permalink":"/publish/Markdown-常用内容总结/","dgPassFrontmatter":true}
---


>  https://markdown.com.cn/
>  
>  https://markdown.com.cn/cheat-sheet.html 速查表
>  
>  https://publish.obsidian.md/help-zh/编辑与格式化/基本格式语法
>  
>  https://forum-zh.obsidian.md/t/topic/435/1



## 1. 速查表 cheat-sheet

### 1.1. 基本语法

- 标题、块引用、粗斜体
- 列表
- 代码、分割线
- 链接、图片

![assets/publish/Markdown-常用内容总结/IMG-20241219-192913268-1.png](/img/user/assets/publish/Markdown-%E5%B8%B8%E7%94%A8%E5%86%85%E5%AE%B9%E6%80%BB%E7%BB%93/IMG-20241219-192913268-1.png)

### 1.2. 扩展语法

- 删除线 `~~内容~~`
- 代码块 

![assets/publish/markdown-常用内容总结/IMG-20241219-193501325.png](/img/user/assets/publish/Markdown-%E5%B8%B8%E7%94%A8%E5%86%85%E5%AE%B9%E6%80%BB%E7%BB%93/IMG-20241219-193501325.png)

---

## 2. 常用语法
### 2.1. 有序列表、无序列表、列表中嵌套内容

```
有序列表
	1. xxx // {数字}{.}{空格}[内容]  开始数字必须是1
	2. xxx

无序列表
	- xxx //{-}{空格}[内容]
	- xxx
列表中嵌套
	- xxx
	(tab|4空格)[内容]
```
 
### 2.2. 代码

```
短语用`包围

代码块用```包围
```


## 3. 常见问题

### 3.1. markdown 中的空格不能达到对其效果？

### 3.2. markdown 中的标题如何使用？

- 语法上支持`#`到`######`对应`h1-h6`
- 实际写作建议不超过3级标题

一级标题 表示 书名，必有且全局唯一。

如obsidian中，文件中不用写`#`，直接`##`开始，因为obsidian默认会把文件名作为`#`再文件顶部显示。

- 书名(文档总标题)
	- 章节名(模块名)，用于划分大的内容板块。
		- 小节名(子话题)，用于进一步细分逻辑点。

最佳实践：
- 标题后空行：为了兼容性，`#`后加空格，标题下方留一空行。
- 简洁：标题用来导航，标题15字以内。
- 好的文档结构像一棵树：1个主干(h1)，3-7个粗干(h2)，若干细枝(h3)。如果需要更多层级，创建一个新的树。
