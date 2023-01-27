---
title: "[Javascript] Number Methods "
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-01-27T08:06:00-05:00
---

In this post, it tells you about some of methods related in Number.

# .toFixed

It converts a number to a character that represents up to a specified fixed-point mark (digit).

```javascript
const num = 1.23456
console.log(num.toFixed(4)) //1.2345
```

# .toLocaleString()

It returns the number as a character in the local language format.

```javascript
const num = 12345678
console.log(num.toLocaleString()) //12,345,678
```

# .isInteger()

It verifies that the data is an integer.

```javascript
const num1 = 123
const num2 = 1.23

console.log(Number.isInteger(num1)) //true
console.log(Number.isInteger(num2)) //false
```

# .isNaN()

It verifies that the data is not a number.

```javascript
const num1 = NaN
const num2 = 123

console.log(Number.isInteger(num1)) //true
console.log(Number.isInteger(num2)) //false
```

# .parseInt()

It parses a given value (number, letter) and return it as an integer of a specific integer (radix).

```javascript
const num = 123.456
const str = '123.456'

console.log(Number.parseInt(num, 10)) //123 -> integer
console.log(Number.parseInt(str, 10)) //123 -> string
```

# .parseFloat()

It parses the given values (numbers, characters) and return them by floating point mistake.

```javascript
const num = 123.456
const str = '123.456'

console.log(Number.parseFloat(num)) //123.456 -> integer
console.log(Number.parseFloat(str)) //123.456 -> string
```

Thank you!

[Reference]

- every method is in mdn web docs : <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number>
