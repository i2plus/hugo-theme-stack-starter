---
title: Markdown 语法指南
date: 2024-01-01
description: 展示基本 Markdown 语法和 HTML 元素格式的文章示例。
tags: 
    - markdown
    - css
    - html
    - themes
categories:
    - themes
    - syntax
---

本文提供了可在 Hugo 内容文件中使用的基本 Markdown 语法示例，还展示了 Hugo 主题中是否使用 CSS 装饰基本 HTML 元素。

<!--more-->

## 标题

以下的HTML `<h1>` - `<h6>` 元素代表了六个不同级别的章节标题。 `<h1>` 是最高级别的标题，而 `<h6>` 是最低级别的。

# H1
## H2
### H3
#### H4
##### H5
###### H6

## 段落

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## 块引用

blockquote 元素表示从其他来源引用的内容，可以选择包含必须位于 `footer` 或 `cite` 元素内的引文，也可以选择包含注释和缩写等内联更改。

### 没有归属的块引用

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.<br>
>**请注意**，您可以在块引用中使用 *Markdown 语法*。

### 带归属的块引用

> Don't communicate by sharing memory, share memory by communicating.<br>
> 译：不要通过共享内存来通信，而是通过通信来共享内存。<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: 以上引文摘自 Rob Pike 在 2015 年 11 月 18 日 Gopherfest 期间的[演讲](https://www.youtube.com/watch?v=PAAkCSZUG1c)。

## 表格

表格不是核心 Markdown 规范的一部分，但 Hugo 支持开箱即用。

   姓名 | 年龄
--------|------
   小红 | 27
   小明 | 23

### 表格内内联 Markdown

| 斜体   | 加粗     | 代码   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

| A                                                        | B                                                                                                             | C                                                                                                                                    | D                                                 | E                                                          | F                                                                    |
|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------|
| Lorem ipsum dolor sit amet, consectetur adipiscing elit. | Phasellus ultricies, sapien non euismod aliquam, dui ligula tincidunt odio, at accumsan nulla sapien eget ex. | Proin eleifend dictum ipsum, non euismod ipsum pulvinar et. Vivamus sollicitudin, quam in pulvinar aliquam, metus elit pretium purus | Proin sit amet velit nec enim imperdiet vehicula. | Ut bibendum vestibulum quam, eu egestas turpis gravida nec | Sed scelerisque nec turpis vel viverra. Vivamus vitae pretium sapien |

## 代码块
### 带反引号的代码块

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

### 代码块缩进四个空格

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

### 差异代码块

```diff
[dependencies.bevy]
git = "https://github.com/bevyengine/bevy"
rev = "11f52b8c72fc3a568e8bb4a4cd1f3eb025ac2e13"
- features = ["dynamic"]
+ features = ["jpeg", "dynamic"]
```

### 一行代码块

```html
<p>A paragraph</p>
```

## 列表类型

### 有序列表

1. 第一项
2. 第二项
3. 第三项

### 无序列表

* 项目清单
* 另一项
* 还有另一项

### 嵌套列表

* 水果
  * 苹果
  * 橙子
  * 香蕉
* 奶制品
  * 牛奶
  * 奶酪

## 其他元素  — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> 是一种位图图像格式.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

按  <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> 结束会话.

大多数<mark>蝾螈</mark>是夜间活动的，捕食昆虫、蠕虫和其他小生物