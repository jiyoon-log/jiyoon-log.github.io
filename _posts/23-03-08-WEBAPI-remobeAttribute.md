---
title: "[Web APIs] Element.removeAttribute()"
excerpt: ""

categories:
  - WEBAPI
tags:
  - WEBAPI
last_modified_at: 2023-03-08T08:06:00-05:00
---

In this post, it tells you about some of Element.removeAttribute&#40;&#41;.

# Element.removeAttribute&#40;&#41;

It removes the attribute with the specified name from the element. 
(from MDN page)

# Syntax

```javascript
removeAttribute(attrName)
```

# Example

```javascript
// Given: <div id="d1" align="right" width="400px">
document.getElementById("d1").removeAttribute("align");
// Now: <div id="d1" width="400px">
```



Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/removeAttribute>
