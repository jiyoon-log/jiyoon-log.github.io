---
title: "[Javascript] Object.keys()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-25T08:06:00-05:00
---

In this post, it tells you about some of Object.keys&#40;&#41;.

# Object.keys&#40;&#41;

It returns the string-keyed of object.


# Syntax

```javascript
Object.keys(obj)
```

## Parameter
- object : object


# Example
Example is from mdn page of Object.prototype.isPrototypeOf&#40;&#41;.

```javascript
const object1 = {
  a: 'hello',
  b: 22,
  c: true
};

console.log(Object.keys(object1));
// Expected output: Array ["a", "b", "c"]
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys>
