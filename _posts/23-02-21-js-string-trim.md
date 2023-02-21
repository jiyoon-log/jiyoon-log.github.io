---
title: "[Javascript] String.prototype.trim()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-21T08:06:00-05:00
---

In this post, it tells you about some of String.prototype.trim&#40;&#41;.

# String.prototype.trim&#40;&#41;

It returns the new string that removes the front and back blank from the origin string.
It doesn't touch the origin string. 


# Syntax

```javascript
trim()
```

# Example
Example is from mdn page of String.prototype.search.

```javascript
const str = "   hello  ";
console.log(str.trim()); // 'hello'
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/Trim>
