---
title: "[CSS] box-shadow"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-10T08:06:00-05:00
---

In this post, it tells you about some of 'box-shadow'.

# box-shadow

It is for adding shadows to HTML elements.

# Syntax 
```css
box-shadow: [h-offset] [v-offset] [blur] [spread] [color] (inset);
```

| <filter-function> values | Explanation                     |
| ------------------------ | ------------------------------- |
| h-offset      | Setting the Shadow's Left and Right  |
| v-offset     | Setting the Shadow's Up and Down  |
| blur    |  the extent of the shadow's   |
| spread   | the size of the shadow    |
| color  | Shadow color |
| inset | (optional) Shadow representation inside the element, by default shadow is located outside the element |


# Example

```html
<div class="box" id="first">
			box-shadow: 5px 5px 5px black
</div>
<div class="box" id="second">
			box-shadow: 100px 20px teal
</div>
```

```css
.box {
  width: 200px;
  height: 50px;
  background-color: pink;
  text-align: center;
  line-height: 50px;
  box-shadow: 5px 5px 5px black;
  font-size: 10px;
  margin-bottom: 10px;
}
#second {
  box-shadow: 100px 20px teal;
}
```

# Result

![css-box-shadow-ex](/assets/img/css-box-shadow-ex.PNG)

Thank you!

[Reference]

- modueimanual: <http://triki.net/prgm/3227>
