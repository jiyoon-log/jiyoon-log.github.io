---
title: "[CSS] transform: translate "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-04T08:06:00-05:00
---

In this post, it tells you about some of 'transform'.

# transform

The transform property is basically used to move an element along the X and Y axes by a specified distance.

# Syntax

```css
user-select: translate(x, y) | translateX() | translateY() | translateZ() |
  translate3d();
```

# transform value

| <filter-function> values | Explanation                                                                       |
| ------------------------ | --------------------------------------------------------------------------------- |
| translate(x, y)          | Position elements relative to x distance and y distance                           |
| translateX()             | Specify the value of the travel distance from side to side (horizontal direction) |
| translateY()             | Specify the vertical (vertical) travel distance value                             |
| translateZ()             | Specify travel by distance in Z direction                                         |
| translate3d(x,y,z)       | Move by the distance of the given x-axis, y-axis and z-axis.                      |

# Example

```html
<div class="container">
  <div class="box" id="translate">translate(x, y)</div>
  <div class="box" id="translateX">translateX(x)</div>
  <div class="box" id="translateY">translateY(y)</div>
</div>
```

```css
.container {
  width: 300px;
  height: 200px;
  background-color: pink;
  border: solid 8px;
}
.box {
  width: 100px;
  height: 30px;
  background-color: white;
  border: solid 2px;
}

#translate {
  transform: translate(100px, 0);
}
#translateX {
  transform: translateX(200px);
}
#translateY {
  transform: translateY(100px);
}
```

![transform-translate-ex](/assets/img/transform-translate-ex.PNG)

Thanks.

[Reference]

- TABMODe: <https://www.tabmode.com/homepage/transform-translate.html>
