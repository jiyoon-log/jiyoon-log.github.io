---
title:  "[CSS] justify-content "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-31T08:06:00-05:00
---

In this post, it tells you about 'justify-content'.

# justify-content

The justify-content property sets the horizontal alignment of the flex elements.


# justify-content value

- flex-start : default, flex property positioned from the front of the flex container
- flex-end: flex element is positioned from the rear of the flex container
- center : flex element is positioned from the center of the flex container
- space-between : flex element is placed with free space only between the element
- space-around : flex elements are placed with free space in front, back, and between the elements

# Example

```html
	<div class="box-container" id="flex-start">
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
	</div>
	<div class="box-container" id="flex-end">
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
	</div>
	<div class="box-container" id="center">
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
	</div>
	<div class="box-container" id="space-between">
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
	</div>
	<div class="box-container" id="space-around">
		<div class="box"></div>
		<div class="box"></div>
		<div class="box"></div>
	</div>
```

```css
.box-container {
  display: flex;
  border: 2px solid darkblue;
  width: 200px;
  height: 50px;
}
.box {
  width: 40px;
  height: 30px;
  border: 2px solid red;
  margin: 10px 0 0 0;
}
#flex-start {
  justify-content: flex-start;
}
#flex-end {
  justify-content: flex-end;
}
#center {
  justify-content: center;
}
#space-between {
  justify-content: space-between;
}
#space-around {
  justify-content: space-around;
}
```

# Result
![justify-content-ex](/assets/img/justify-content-ex.PNG)

Thanks.

[Reference]
* TCPschool.com: <http://www.tcpschool.com/css/css3_expand_flexbox>

