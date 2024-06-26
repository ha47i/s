# 基础用法文档

## 基础用法

`#`数量为1-6，对应HTML的h1-h6。

你也可以使用`见下`来换行。

```
<br>
```

[链接](https://github.com)

<https://github.com>

https://github.com

**粗体Text**，*斜体Text iiii*，***又粗又斜***。

如果以上用法用在整个段落或句子中，可将`*`替换为`_`。

> 引用是这样的
> 多行时在换行符里也要加">"。
>
>> 也可以套娃。
>
>> - 甚至是其他样式...

[Markdown基本语法](https://markdown.com.cn/basic-syntax/)

---

- 1
	- 2
		- 3
			- 4

```css
text
	text
```

## 列表

稍许复杂，请看[这里](https://markdown.com.cn/basic-syntax/lists.html)。

## 附加用法

在图片控件后面加`{width="300"}`，可以修改图片的展示效果。

第一张图片是带链接的。

[![](./1.png){width="300"}](https://github.com)

![](./1.png){width="50%"}

![](./1.png){width="40%"}
![](./1.png){width="40%"}

## 卡片

<div class="grid cards" markdown>

-   <img src="../1.png"/> __卡片标题__
    
    ---

    [一条链接](https://github.com)

</div>