---
title:  "[CSS] CSS display properties (inline, block, inline-block) "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-23T08:06:00-05:00
---

In this post, it tells you little bit of what is inline, block, inline-block.
They are the properties of the display.

# CSS inline

The "inline" property makes the specified elements placed alongside the other elements in one line.
Example html tags are <span>, <a>, <em>. 
There are more. 

```html
<span>apple</span>
<span>banana</span>
<a href="https://google.com">google</a>
```
```css
span {
  width: 200px;
  height: 100px;
  margin: 20px;
  padding: 20px;
  color: white;
  background-color: #262626;
}
```

![inline_ex](/assets/img/inline_ex.PNG)

As you can see, if the tag has the inline properties, width and height don't work. 
But margin and padding are working (only left&right, not hight and width). 
This is because the tag is supposed to take up space only by the size of the content being marked up.


# CSS block 

The "block" property makes elements designated occupy the entire line.
Example html tags are <div>, <p>, <h1>.
There are more.

```html
<h1>fruit</h1>
<div>apple</div>
<p>banana</p>
<h4>google</h4>
```

```css
div, p, h1, h4 {
  width: 200px;
  height: 30px;
  margin: 20px;
  padding: 20px;
  color: white;
  background-color: #262626;
}
```

![block_ex](/assets/img/block_ex.PNG)

As you can see, if the tag has the block properties, width and height work. 
Also, margin and padding are working either left&right and hight&width. 


# inline-block
The "inline-block" property makes the specified elements placed alongside the other elements in one line like "inline",
but like "block" elements it can have the width&height.  
Example html tags are button, input, select.
There are more.

```html
<button>fruit</button>
<input>apple</input>
<select>banana</select>
```

```css
button, input {
  width: 100px;
  height: 30px;
  margin: 20px;
}
select {
  width: 50px;
  height: 30px;
  margin: 20px;
  color: white;
  background-color: #666;
}
```
![inline_block_ex](/assets/img/inline_block_ex.PNG)

As you can see, it follows the rules of the block element internally and externally the rules of the inline element.

Thanks

[Reference]
* DaleSeo: <https://www.daleseo.com/css-display-inline-block/>
