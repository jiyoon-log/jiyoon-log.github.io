---
title: "[Web APIs] Element.before()"
excerpt: ""

categories:
  - WEBAPI
tags:
  - WEBAPI
last_modified_at: 2023-03-03T08:06:00-05:00
---

In this post, it tells you about some of Element.before&#40;&#41;.

# Element.before&#40;&#41;

It inserts a set of Node or string object before the parent object.

# Syntax

```javascript
before(param1)
before(param1, param2)
before(param1, param2, /* … ,*/ paramN)
```

# Example
Example is from mdn page of Element.before&#40;&#41;.

## Inserting an element

```javascript
let box1 = document.createElement("h1");
let box2 = document.createElement("h2");
box1.appendChild(box2);
let box3 = document.createElement("h3");

box2.before(box3);

console.log(box1.outerHTML);
// "<h1><h3></h3><h2></h2></h1>"
```

## Inserting text
```javascript
let box1 = document.createElement("div");
box1.before("Example");

console.log(box1.outerHTML);
// "Example<div></div>"
```


Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/before>
