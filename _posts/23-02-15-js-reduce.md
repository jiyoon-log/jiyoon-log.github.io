---
title: "[Javascript] Array.prototype.reduce()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-15T08:06:00-05:00
---

In this post, it tells you about some of Array.prototype.reduce.

# Array.prototype.reduce&#40;&#41;

It runs a given reducer function for each element in the array and returns one result.

## callback function

- accumulator &#58; Accumulates the return value of the callback function.
- currentValue &#58; Current Elements of an Array
- index&#40;option&#41; &#58; Index of the current element of the array
- array&#40;option&#41; &#58; Called array

# Syntax

```javascript
    arr.reduce(callback[, initialValue])
```

# Example

```javascript
const nums = [[4,6],[2,8]]

flatNums = nums.reduce((acc,curr) => acc.concat(curr), []) //[4,6,2,8]
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce>
