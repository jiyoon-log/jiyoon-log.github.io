---
title: "[Javascript] Object.prototype.toString()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-27T08:06:00-05:00
---

In this post, it tells you about some of Object.prototype.toString&#40;&#41;.

# Object.prototype.toString&#40;&#41;

It returns a string representing the object.


# Syntax

```javascript
toString()
```


# Example
Example is from mdn page of Object.prototype.isPrototypeOf&#40;&#41;.

```javascript
const arr = [4, 5, 6];

arr.toString(); // "4,5,6"
Object.prototype.toString.call(arr); // "[object Array]"
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString>
