TOPIC: markdown

# Markdown

**Markdown** is a simple markup language that allows one to write documents
using a text editor and transform those documents into many different formats,
such as *HTML*, *Word*, images, *PDF*, *epub*, etc.
Among other things, it works beautifully for documenting source code since the
Markdown documents can be checked in and versioned with *Git* or your source
control system of choice.

Markdown language is created by *John Gruber* in 2004.

!!! info "Tips"
    The *suffix* of the documents written by Markdown are `.md` or `.markdown`.

## Heading

!!! info "Standard Markdown"
    This is the *standard Markdown* syntax.

```markdown
# Level-1 Heading

## Level-2 Heading

### Level-3 Heading
```

```html
<h1>Level-1 Heading</h1>

<h2>Level-2 Heading</h2>

<h3>Level-3 Heading</h3>
```

## Paragraph

!!! info "Standard Markdown"
    This is the *standard Markdown* syntax.

```markdown
Paragraph 1

Paragraph 2
```

```html
<p>Paragraph 1</p>
<p>Paragraph 2</p>
```

## List

!!! info "Standard Markdown"
    This is the *standard Markdown* syntax.

### Unordered List

```markdown
- Item 1
  - Item 1.1
  - Item 1.2
- Item 2
```

```html
<ul>
  <li>Item 1</li>
  <ul>
    <li>Item 1.1</li>
    <li>Item 1.2</li>
  </ul>
  <li>Item 2</li>
</ul>
```

### Ordered List

```markdown
1. Item 1
1. Item 2
```

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
```

### Definition List

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

## Text

### Bold Text

!!! info "Standard Markdown"
    This is the *standard Markdown* syntax.

```markdown
This text will be **bold**

This will also be __bold__
```

```html
This text will be <strong>bold</strong>

This will also be <strong>bold</strong>
```

### Italic Text

!!! info "Standard Markdown"
    This is the *standard Markdown* syntax.

```markdown
*This text will be italic*

_This will also be italic_
```

```html
<em>This text will be italic</em>

<em>This will also be italic</em>
```

### Deleted Text

!!! info "Standard Markdown"
    This is the *standard Markdown* syntax.

```markdown
~~Deleted Text~~
```

```html
<del>Deleted Text</del>
```

### Inserted Text

!!! warn "Dookbook Markdown"
    This is the *Dookbook Markdown* syntax.

```markdown
++Inserted Text++
```

```html
<ins>Inserted Text</ins>
```

### Combined Emphasis Text

!!! warn "Dookbook Markdown"
    This is the *Dookbook Markdown* syntax.

```markdown
Combined emphasis with **asterisks and _underscores_**.
```

```html
Combined emphasis with <strong>asterisks and <em>underscores</em></strong>.
```

## References

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Writing on GitHub](https://help.github.com/categories/writing-on-github/)
