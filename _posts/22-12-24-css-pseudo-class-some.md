---
title:  "[CSS] CSS pseudo-class "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-24T08:06:00-05:00
---

In this post, it tells you some of pseudo-class in CSS.

# CSS pseudo-class

You can attach a virtual event after a selector to set the style to apply for each particular event.

- :hover - when you roll over the mouse
- :active - when you click the mouse
- :focus - when focused with the mouse
- :link - a link that has never been visited
- :visted - a link that has been visited
- :first - first element
- :last - last element
- :first-child - first child in group
- :last-child - last child in group
- :nth-child(2n+1) - odd-numbered child

# Example 

```html
<div class="box hover">hover ex (bring your mouse cursor)</div>
  <input class="focus" type="text" value="focus ex (click it)"/>
  <div class="container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
  </div>
```

```css
.box{
  background-color: lightpink;
  padding: 10px;
  margin-bottom: 10px;
}
.hover:hover{
  background-color: orange;
}
.focus:focus{
  background: yellowgreen;
}

.container > div{
  margin-top: 10px;
  margin-right: 20px;
  width: 100px;
  height: 50px;
  float: left;
  padding: 30px 0px 0px;
  background-color: skyblue;
  text-align: center;
}
.container > div:nth-child(2n+1) {
  background-color: darkorchid;
}
```

# Result

![before_pseudo](/assets/img/before_pseudo.PNG)

![after_pseudo](/assets/img/after_pseudo.PNG)

There are many other qseudo class in CSS.

Thanks.

[Reference]
* ofcouse: <https://ofcourse.kr/css-course/%EA%B0%80%EC%9E%A5-%ED%81%B4%EB%9E%98%EC%8A%A4-%EC%84%A0%ED%83%9D%EC%9E%90>
