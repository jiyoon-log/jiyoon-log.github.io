---
title: "[CSS] font-family"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-24T08:06:00-05:00
---

In this post, it tells you about some of font
&#45;family.

# font-family

It is for setting which font family and generic family on text.

# Syntax

```css
/* A font family name and a generic family name */
font-family: Gill Sans Extrabold, sans-serif;

/* A generic family name only */
font-family: serif;

/* Global values */
font-family: inherit;
font-family: initial;
```

# Example

```html
<p class="sansserif">sanserif</p>
<p class="serif">serif</p>
<p class="cursive">cursive</p>
<p class="monospace">monospace</p>
<p class="fantasy">fantasy</p>
```

```css
.serif {font-family: Times, Times New Roman, Georgia, serif;}
.sansserif {font-family: Verdana, Arial, Helvetica, sans-serif;}
.monospace {font-family: Lucida Console, Courier, monospace;}
.cursive {font-family: cursive;}
.fantasy {font-family: fantasy;}
```

# Result

![css-font-family-ex](/assets/img/css-font-family-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/CSS/font-family>
