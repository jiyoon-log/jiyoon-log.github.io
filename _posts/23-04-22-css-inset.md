---
title: "[CSS] inset"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-04-22T08:06:00-05:00
---

In this post, it tells you about some of 'inset'.

# inset

The 'inset' displays the child nodes at regular intervals.


# Example

```html
<div class="parent" >
  <div class="child">
  </div>
</div>
```

```css
.parent{
  position: relative;
  width:200px;
  height: 200px;
  background-color: skyblue;
}
.child {
  position: absolute;
  inset: 2em;
  background-color: pink;
}
```

# Result

![css-inset](/assets/img/css-inset.PNG)

Thank you!

[Reference]

- smilehugo: <https://smilehugo.tistory.com/entry/display-child-node-inside-of-parent-node-using-css-inset-property>
