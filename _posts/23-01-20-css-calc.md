---
title: "[CSS] calc"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-20T08:06:00-05:00
---

In this post, it tells you about some of 'calc'.

# calc

It is for calculating the amount for user.

# Example

```html
<div id="box1" class="box">box1</div>
<div id="box2"  class="box">box2</div>
<div id="box3"  class="box">box3</div>
```

```css
body {background-color:lightpink;}
#box1 {
  width:calc(10px + 30px);
  background-color:red;
  color:white;
}
#box2 {
  width:calc(100% - 100px);
  background-color:orange;
  color:white;
}
#box3 {
  width:calc(50% - 20px);
  background-color:yellow;
  color:brown;
}
```

# Result

![css-calc-ex](/assets/img/css-calc-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/calc>
