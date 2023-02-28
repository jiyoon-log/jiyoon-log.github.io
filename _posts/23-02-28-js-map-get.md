---
title: "[Javascript] Map.prototype.get()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-28T08:06:00-05:00
---

In this post, it tells you about some of Map.prototype.get&#40;&#41;.

# Map.prototype.get&#40;&#41;

It returns the element from Map object.


# Syntax

```javascript
get(key)
```

## Parameter
- key : key of the object that the user wants to know.


# Example
Example is from mdn page of Map&#40;&#41; constructor.

```javascript
const myMap = new Map();
myMap.set('bar', 'foo');

console.log(myMap.get('bar')); // Returns "foo"
console.log(myMap.get('baz')); // Returns undefined
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/get>
