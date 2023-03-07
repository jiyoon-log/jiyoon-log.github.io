---
title: "[Web APIs] Element.remove()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-03-07T08:06:00-05:00
---

In this post, it tells you about some of Element.remove&#40;&#41;.

# Element.remove&#40;&#41;

It removes the element from the DOM.

# Syntax

```javascript
remove()
```

# Example

```html
<div id="d1">d1</div>
<div id="d2">d2</div>
<div id="d3">d3</div>
```


```javascript
const element = document.getElementById("d2");
element.remove(); // Removes the div with the 'd2' id
```



Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/remove>
