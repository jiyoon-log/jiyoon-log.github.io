---
title: "[Javascript] XOR assignment"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-09T08:06:00-05:00
---

In this post, it tells you about some of XOR assignment &#94;&#61;.

# XOR assignment &#94;&#61;

The XOR assignment operator works in bitwise. 

# Syntax

```javascript
a ^= b // a = a ^ b
```

# Example 
in mdn pages

```javascript
let a = 5; // (00000000000000000000000000000101)
a ^= 3; // (00000000000000000000000000000011)

console.log(a); // 6 (00000000000000000000000000000110)

let b = 5; // (00000000000000000000000000000101)
b ^= 0; // (00000000000000000000000000000000)

console.log(b); // 5 (00000000000000000000000000000101)
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_XOR_assignment>
