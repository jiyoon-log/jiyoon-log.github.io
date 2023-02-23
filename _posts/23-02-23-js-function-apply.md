---
title: "[Javascript] Function.prototype.apply()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-23T08:06:00-05:00
---

In this post, it tells you about some of Function.prototype.apply&#40;&#41;.

# Function.prototype.apply&#40;&#41;

It calls the specified function with a given this value, and arguments provided as an array (or an array-like object). (from mdn pages)


# Syntax

```javascript
apply(thisArg)
apply(thisArg, argsArray)
```

# Example
Example is from mdn page of Function.prototype.apply.

```javascript
const array = ["a", "b"];
const elements = [0, 1, 2];
array.push.apply(array, elements);
console.info(array); // ["a", "b", 0, 1, 2]
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply>
