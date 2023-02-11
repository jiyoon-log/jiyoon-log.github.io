---
title: "[Javascript] Equality"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-11T08:06:00-05:00
---

In this post, it tells you about some of Equality&#61;&#61;.

# Equality

The Equality operator checks the two operands are equal, or not. 
It returns a boolean result.

# Syntax

```javascript
x == y
```

# Example 
All examples are from mdn pages of Equality.

## Comparison with type conversion

```javascript
"1" == 1; // true
1 == "1"; // true
0 == false; // true
0 == null; // false
0 == undefined; // false
0 == !!null; // true, look at Logical NOT operator
0 == !!undefined; // true, look at Logical NOT operator
null == undefined; // true
```

## Comparison of Objects

```javascript
const obj1 = {key: "value"}
const obj2 = {key: "value"}

console.log(obj1 == obj2); // false
console.log(obj1 == obj1); // true
```

## Comparison strings & String objects

```javascript
const str1 = "hi";
const str2 = String("hi");
const str3 = new String("hi");
const str4 = new String("hi");

console.log(str1 == str2); // true
console.log(str1 == str3); // true
console.log(str2 == str3); // true
console.log(str3 == str4); // false
console.log(str4 == str4); // true
```

## Comparison array and strings

```javascript
const e = [4, 5, 6];
const f = "4,5,6";
e == f; // true, `a` converts to string

const g = [false, 1.3, "ho"];
const h = c.toString(); // "false,1.3,ho"
g == h; // true
```


Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Equality>
