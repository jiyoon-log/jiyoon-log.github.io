---
title: "[Web APIs] Element.setAttributeNode()"
excerpt: ""

categories:
  - WEBAPI
tags:
  - WEBAPI
last_modified_at: 2023-03-12T08:06:00-05:00
---

In this post, it tells you about some of Element.setAttributeNode&#40;&#41;.

# Element.setAttributeNode&#40;&#41;

It adds a new Attr node to the specified element.
(from MDN page)

# Syntax

```javascript
setAttributeNode(attribute)
```

# Example
The example is from the mdn page.

```html
<div id="one" align="left">one</div>
<div id="two">two</div>
```

```javascript
let e1 = document.getElementById("one");
let e2 = document.getElementById("two");
let b = e1.getAttributeNode("align");

e2.setAttributeNode(b.cloneNode(true));

// Returns: 'left'
alert(e2.attributes[1].value);
```



Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttributeNode>
