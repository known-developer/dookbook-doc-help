TOPIC: markdown

# Markdown

**Markdown**是一种轻量级的标记语言。通过简单的标记语法，它允许人们使用易读易写的纯文本格式编写文档，并可转换成各种不同的文档格式
（例如：*HTML*, *Word*, 图片, *PDF*, *epub*等）。
同时，由于它能够非常方便地被*Git*或其他版本控制系统进行版本控制，所以非常适合作为源代码的文档编写语言。它也经常被许多论坛、博客主用来编辑论坛贴和博客内容。

Markdown语言在2004由*约翰·格鲁伯*创建。

!!! info "小贴士"
    Markdown编写的文档*后缀*为`.md`或`.markdown`。

## 标题

!!! info "标准Markdown"
    此为*标准Markdown*语法。

```markdown
# 一级标题

## 二级标题

### 三级标题
```

```html
<h1>一级标题</h1>

<h2>二级标题</h2>

<h3>三级标题</h3>
```

## 段落

!!! info "标准Markdown"
    此为*标准Markdown*语法。

```markdown
段落1

段落2
```

```html
<p>段落1</p>
<p>段落2</p>
```

## 列表

!!! info "标准Markdown"
    此为*标准Markdown*语法。

### 无序列表

```markdown
- 列表项目 1
  - 列表项目 1.1
  - 列表项目 1.2
- 列表项目 2
```

```html
<ul>
  <li>列表项目 1</li>
  <ul>
    <li>列表项目 1.1</li>
    <li>列表项目 1.2</li>
  </ul>
  <li>列表项目 2</li>
</ul>
```

### 有序列表

```markdown
1. 列表项目 1
1. 列表项目 2
```

```html
<ol>
  <li>列表项目1</li>
  <li>列表项目2</li>
</ol>
```

### 定义列表

```markdown
Apple
:   Pomaceous fruit of plants of the genus Malus in
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.
```

```html
<dl>
  <dt>Apple</dt>
  <dd>Pomaceous fruit of plants of the genus Malus in the family Rosaceae.</dd>

  <dt>Orange</dt>
  <dd>The fruit of an evergreen tree of the genus Citrus.</dd>
</dl>
```

## 文本

### 强调文本

!!! info "标准Markdown"
    此为*标准Markdown*语法。

!!! warn
    双下划线`__`不支持中文!

```markdown
这是**强调文字**

这不支持中文__强调文字__
```

```html
这是<strong>强调文字</strong>

这不支持中文<strong>强调文字</strong>
```

### 斜体文本

!!! info "标准Markdown"
    此为*标准Markdown*语法。

```markdown
*次强调文字， 斜体*

_这也是次强调文字，斜体_
```

```html
<em>次强调文字， 斜体</em>

<em>这也是次强调文字，斜体</em>
```

### 删除文本

!!! info "标准Markdown"
    此为*标准Markdown*语法。

```markdown
~~删除的文字~~
```

```html
<del>删除的文字</del>
```

### 插入文本

!!! warn "Dookbook Markdown"
    此为*Dookbook Markdown*语法。

```markdown
++插入的文字++
```

```html
<ins>插入的文字</ins>
```

### 混合文本

!!! warn "Dookbook Markdown"
    此为*Dookbook Markdown*语法。

```markdown
混合的文本**强调和 _斜体_**.
```

```html
混合的文本<strong>强调和 <em>斜体</em></strong>.
```

## 水平分割线

!!! info "标准Markdown"
    此为*标准Markdown*语法。

```markdown
***
```

```html
<hr/>
```

## 链接

```markdown
[链接文字](URL)

[链接文字](URL "提示文字")
```

```html
<a href="URL">链接文字</a>

<a href="URL" title="提示文字">链接文字</a>
```

## 参考资料

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Writing on GitHub](https://help.github.com/categories/writing-on-github/)
