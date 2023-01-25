---
title: "[Javascript] Conditional Operator"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-01-25T08:06:00-05:00
---

In this post, it tells you about some of Conditional Operator.

# Conditional Operator

It has the three operands. 
From the first, there are the conditional statement before the question mark, the statement that is executing if the conditional statement is true, and the last statement is for the conditional statement is false. 

# Syntax

```javascript
 condition ? exprIfTrue : exprIfFalse
```

# Example

```javascript
let time = 20
let timer = (time >= 19) ? 'ready' : 'not'
console.log(timer) // ready
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Operators/Conditional_Operator>
