---
title: "[Javascript] And assignment(&=)"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-05T08:06:00-05:00
---

In this post, it tells you about some of And assignment &#38;	&#61;.

# And&#38;&#61;

The And assignment operator works in bitwise.   
It performs a bitwise AND operation on the operand and assign the result to the variable.

# Syntax

```javascript
a &= b // a = a & b
```

# Example 

```javascript
let a = 5;
// 5:     00000000000000000000000000000101
// 2:     00000000000000000000000000000010
a &= 2; // 0
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_AND_assignment>
