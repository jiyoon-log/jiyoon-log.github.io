---
title: "[Web APIs] Element.setAttribute()"
excerpt: ""

categories:
  - WEBAPI
tags:
  - WEBAPI
last_modified_at: 2023-03-11T08:06:00-05:00
---

In this post, it tells you about some of Element.setAttribute&#40;&#41;.

# Element.setAttribute&#40;&#41;

It sets the value of an attribute on the specified element
(from MDN page)

# Syntax

```javascript
setAttribute(name, value)
```

# Example
The example is from the mdn page.

```html
<button>Hello World</button>
```

```javascript
const button = document.querySelector("button");

button.setAttribute("name", "helloButton");
button.setAttribute("disabled", "");
```



Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute>
