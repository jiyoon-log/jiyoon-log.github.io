---
title:  "[CSS] Align text in <div> "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-27T08:06:00-05:00
---

In this post, it tells you how to align text in <div>.

# To align horizontally

For align horizaontally, we can use "text-align" or "justify-content".
If display property sets flex, use justify-content. 
The reason is that the text-align doesn't work.

- text-align:center; 
- justify-content:center; 

# Example

```html
	<div class="box-container">
		<div id="box-text-align">text-align</div>
	</div>
	<div class="box-container">
		<div id="box-justify-content">justify-content</div>
	</div>
```

```css
.box-container {
  width: 200px;
  height: 50px;
  background-color: #9ef3e9;
  margin-bottom: 10px;
}
#box-text-align{ 
  text-align: center; 
}
#box-justify-content{
  display: flex; 
  justify-content: center;
}
```

![align-width-ex](/assets/img/align-width-ex.PNG)

# To align vertically

There are three ways to align vertically.
But, I have problems with two other ways. 
So, in this post, it shows only one way.

- line-height

# Example

```html
<div class="box-container">
	<div id="box-line-height">line-height</div>
</div>
```
```css
.box-container {
  width: 200px;
  height: 100px;
  background-color: #9ef3e9;
  margin-bottom: 10px;
}
#box-line-height{ 
  line-height: 100px;
}
```

![align-height-ex](/assets/img/align-height-ex.PNG)

Thanks.

[Reference]
* hi.anna: <https://hianna.tistory.com/674>
