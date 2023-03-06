---
title: "[Web APIs] Element.hasAttribute()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-03-06T08:06:00-05:00
---

In this post, it tells you about some of Element.hasAttribute&#40;&#41;.

# Element.hasAttribute&#40;&#41;

It returns the boolean value if there is a specified element or not.

# Syntax

```javascript
hasAttribute(name)
```

# Example

```javascript
const h1 = document.getElementById("h2");
if (h1.hasAttribute("hello")) {
  console.log('hello')
}
```



Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/hasAttribute>
