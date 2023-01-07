---
title:  "[CSS] flex-grow "
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-07T08:06:00-05:00
---

In this post, it tells you about some of 'flex-grow'.

# flex-grow

'flex-grow' is a property that fills in the remaining margins when a value greater than 0 is set to a Flexible box.

# Syntax

```css
/* number values */
flex-grow :  <number [0,∞]> ;
flex-grow : 0.2;

/* Global values */
flex-grow : inherit;
flex-grow : initial;
flex-grow : unset;
```

# Example

```css
.container {
  width: 300px;
  height: 50px;
  background-color: pink;
  border: solid;
  display: flex;
}
.box{
  height:50px;
  text-align: center;
  line-height:50px;
  background-color: lightblue;
}
.box:nth-child(2){
  background-color: lightgray;
  flex-grow: 1;
}
.box:nth-child(1){
  background-color: orange;
  flex-grow: 2;
}
```
# Result 

![css-flex-grow-ex](/assets/img/css-flex-grow-ex.PNG)


Thank you!

[Reference]
* moo-you: <https://moo-you.tistory.com/380>