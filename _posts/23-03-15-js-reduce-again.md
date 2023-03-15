---
title:  "[Javascript] Array.prototype.reduce() "
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-03-15T08:06:00-05:00
---

In this post, it tells you about some of Array.reduce.
It is to understand the method again.

# Array.reduce

It runs a given reducer function for each element in the array and returns one result.

# Syntax

```javascript
    arr.reduce(callback[, initialValue])
```


# Example

```javascript
const num = [0,1,2,3,4]

const sum = num.reduce(function(accumulator, currentValue, currentIndex, array) {
  return accumulator + currentValue;
})

// sum = 10
```

Thank you!

[Reference]
* mdn : <https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce>