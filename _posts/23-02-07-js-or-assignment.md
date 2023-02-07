---
title: "[Javascript] OR assignment"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-07T08:06:00-05:00
---

In this post, it tells you about some of OR assignment &#124;	&#61;.

# OR assignment &#124;	&#61;

The OR assignment operator works in bitwise. 

# Syntax

```javascript
a |= b // a = a | b
```

# Example 

```javascript
let a = 5;
a |= 2; // 7
// 5: 00000000000000000000000000000101
// 2: 00000000000000000000000000000010
// -----------------------------------
// 7: 00000000000000000000000000000111
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_OR_assignment>
