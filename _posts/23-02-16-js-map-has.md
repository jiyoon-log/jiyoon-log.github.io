---
title: "[Javascript] Map.prototype.has()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-16T08:06:00-05:00
---

In this post, it tells you about some of Map.prototype.has&#40;&#41;.

# Map.prototype.has&#40;&#41;

It returns true if there is an element with the specified key exists.
If there is not an element with the specified key, it returns false.

# Syntax

```javascript
has(key)
```

- key : the key of the element
- return value : true(if there is an element with specified key), false (otherwise)

# Example

```javascript
const map = new Map();
map.set("first", "hello");

console.log(map.has("first")); // true
console.log(map.has("second")); // false
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/has>
