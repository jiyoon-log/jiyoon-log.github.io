---
title: "[CSS] Display child element in the middle of the parent element"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-04-23T08:06:00-05:00
---

In this post, it tells you about some of 'Display child element in the middle of the parent element'.


# Example

```html
<div class="parent" >
  <div class="child">
  </div>
</div>
```

```css
.parent{
  width:100px;
  height:100px;
  display: table-cell;
  text-align: center;
  vertical-align: middle;
  background-color: pink;
}
.child {
  width: 50px;
  height:50px;
  display: inline-block;
  background-color: red;
}
```

# Result

![css-middle](/assets/img/css-middle.PNG)

Thank you!

[Reference]

- smilehugo: <https://smilehugo.tistory.com/entry/how-to-center-a-div>
