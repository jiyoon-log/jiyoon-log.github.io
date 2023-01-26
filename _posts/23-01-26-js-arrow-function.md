---
title: "[Javascript] Arrow Function"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-01-26T08:06:00-05:00
---

In this post, it tells you about some of arrow function.

# Arrow Function

It is the compact version of function expression

# Syntax

```javascript
x => x*x
(x) => x*x
(x, y) => x*y
x => {return x}
(x, y) => {return x*y}
```

# Example

```javascript

const isBig = num => (num>20 ? 'yes': 'no')
isBig(30) // Yes
isBig(19) // No

const arr = [1,2,3,4,5,6]

const double = arr.map(n => n*2) 
//[2,4,6,8,10,12]
const even = arr.filter(b => b%2 === 0) 
//[2,4,6]

```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions#examples>
