---
title: "[Web APIs] Element.removeAttributeNode()"
excerpt: ""

categories:
  - WEBAPI
tags:
  - WEBAPI
last_modified_at: 2023-03-09T08:06:00-05:00
---

In this post, it tells you about some of Element.removeAttributeNode&#40;&#41;.

# Element.removeAttributeNode&#40;&#41;

It removes the specified attribute from the element. 
(from MDN page)

# Syntax

```javascript
removeAttributeNode(attributeNode)
```

# Example
It is from MDN page.

```javascript
// Given: <div id="bottom" align="center" />
const ex = document.getElementById("bottom");
const rem = ex.getAttributeNode("align");
ex.removeAttributeNode(rem);
// align is now removed: <div id="bottom" />
```



Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/removeAttributeNode>
