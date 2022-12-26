---
title:  "[CSS] text-align "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-26T08:06:00-05:00
---

In this post, it tells you what is text-align.

# text-align

"text-align" sets the horizontal alignment of the box in a block element or table

- left: align left
- right: align right
- center: align center
- justify: align both sides

# Syntax

```css
div {text-align: right;}
```

# Example

```html
	<div class="box-container">
		<div id="box-left">Left Align</div>
	</div>
	<div class="box-container">
		<div id="box-right">Right Align</div>
	</div>
	<div class="box-container">
		<div id="box-center">Center Align</div>
	</div>
```

```css
.box-container {
  width: 300px;
  background-color: #9ef3e9;
  margin-bottom: 10px;
}
#box-left{ text-align: left; }
#box-right{ text-align: right;}
#box-center{ text-align: center;}
```

# Result

![text-align-ex](/assets/img/text-align-ex.PNG)

Thanks.

[Reference]
* ofcourse: <https://ofcourse.kr/css-course/text-align-%EC%86%8D%EC%84%B1>
