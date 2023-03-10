---
title: "[Web APIs] Element.getAttribute()"
excerpt: ""

categories:
  - WEBAPI
tags:
  - WEBAPI
last_modified_at: 2023-03-04T08:06:00-05:00
---

In this post, it tells you about some of Element.getAttribute&#40;&#41;.

# Element.getAttribute&#40;&#41;

It returns the value of a specified attribute on the element.

# Syntax

```javascript
getAttribute(attributeName)
```

# Example
Example is from mdn page of Element.getAttribute&#40;&#41;.

```html
<!-- example div in an HTML DOC -->
<div id="box1">hello!</div>
```

```javascript
// in a console
const example = document.getElementById("box1");
//=> <div id="box1">hello!</div>

const example = example.getAttribute("id");
//=> "box1"

const align = example.getAttribute("align");
//=> null
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/getAttribute>
