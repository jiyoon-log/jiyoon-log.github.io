---
title:  "[CSS] margin & padding "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-25T08:06:00-05:00
---

In this post, it tells you what is margin and padding.

# margin & padding

- margin : outside margin
- padding : inner margin


![margin_padding_ex](/assets/img/margin_padding_ex.PNG)


# Direction 

User can set the margin differently in the direction. 
Below is an example.

```css
div {
  margin:20px // up,down,left,right =20px
  margin:10px 20px // up,down=10px , left,right=20px
  margin:10px 20px 30px 40px //up=10px, right=20px, down=30px, left=40%
  margin:10px 20px 30px //up=10px, right,left=20px, down=30px
}
```
Padding works same way.

# Example

```html
<div class="box-container">
		<div id="box1">margin: 10 <br>padding: 0</div>
	</div>
	<div class="box-container">
		<div id="box2">margin: 10 20<br>padding: 0</div>
	</div>
	<div class="box-container">
		<div id="box3">margin: 0<br>padding: 10 20 30</div>
	</div>
	<div class="box-container">
		<div id="box4">margin: 0<br>padding: 10 20</div>
	</div>
```

```css
.box-container{
  display: inline-block;
  background-color: rgb(219, 252, 231);
  border: 2px solid rgb(48, 204, 0);
  margin: 10px 30px;
}
.box-container div{
  width: 100px;
  height: 50px;
  background-color: rgb(254, 205, 254);
  border: 2px solid rgb(204, 0, 204);
  font-size: 10px;
  text-align: center;
  font-weight: bold;
}
#box1{ margin: 10px;  padding: 0; }
#box2{ margin: 10px 20px; padding: 0; }
#box3{ margin: 0;  padding: 10px 20px 30px; }
#box4{ margin: 0; padding: 10px 20px; }
```

# Result

![margin_padding_res](/assets/img/margin_padding_res.PNG)

Thanks.

[Reference]
* ofcourse: <https://ofcourse.kr/css-course/margin-padding-%EC%86%8D%EC%84%B1>
