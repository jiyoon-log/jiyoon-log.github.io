---
title:  "[Javascript] toFixed "
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-01-05T08:06:00-05:00
---

In this post, it tells you about some of '.toFixed'.

# .toFixed

'.toFixed'methods fixes the number in fixed-point notation.

# Syntax

```javascript
numObj.toFixed([decimal places])
```

Decimal places must be in between 0 to 100.

# Example

```javascript
let numObj = 9.987654

console.log("1. "+ numObj.toFixed()); 
console.log("2. "+ numObj.toFixed(6)); 
console.log("3. "+ numObj.toFixed(3)); 
console.log("4. "+ numObj.toFixed(1)); 
```

# Result 

![toFixed-ex](/assets/img/toFixed-ex.PNG)


Thank you!

[Reference]
* junghn: <https://junghn.tistory.com/entry/JavaScript-%EC%86%8C%EC%88%98%EC%A0%90-%EC%B2%98%EB%A6%AC-%EB%B0%A9%EB%B2%95-toFixed-%EC%82%AC%EC%9A%A9%EB%B2%95%EA%B3%BC-%EC%98%88%EC%A0%9C>
* mdn : <https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Number/toFixed>