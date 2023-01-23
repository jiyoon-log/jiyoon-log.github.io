---
title: "[CSS] text-decoration"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-23T08:06:00-05:00
---

In this post, it tells you about some of text
&#45;decoration.

# text-decoration

It is for decoration on the line(text).

# Syntax

```CSS
text-decoration: underline;
text-decoration: none;
```

# Values

```css
text-decoration-line: underline;
text-decoration-color: black;
text-decoration-style: wavy | solid | dashed;
text-decoration-thickness: 1px;
```

# Example

```html
<p class="under">Line underneath</p>
<p class="over">Line over</p>
<p class="line">Line</p>
<p class="wavyline">Wavy line</p>
<p class="thick">Thick line</p>
<p class="dotted">Dotted line</p>
```

```css
.under {text-decoration: underline red;}
.over {text-decoration: overline orange;}
.line {text-decoration: line-through;}
.wavyline {text-decoration: wavy underline green;}
.thick {text-decoration: solid underline blue 4px;}
.dotted {text-decoration: dotted underline purple 3px;}
```

# Result

![css-text-decoration-ex](/assets/img/css-text-decoration-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration>
