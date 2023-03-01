---
title: "[Javascript] typeof"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-03-01T08:06:00-05:00
---

In this post, it tells you about some of typeof.

# typeof

It returns the string of what is the type of the operand's value.


# Syntax

```javascript
typeof operand
```

## Parameter
- operand : operand that the user wants to know what kind of type is.

# Description

| Type | Result                     |
| ------------------------ | ------------------------------- |
| Undefined | "undefined" |
| Null| "object" |
| Boolean |  "boolean" |
| Number  | "number |
| BigInt | "bigint" |
| String | "string" |
| Symbol | "symbol" |
| Function | "function" |
| Any other object| "object" |


# Example
Example is from mdn page of typeof.

```javascript
// Objects
typeof { a: 1 } === "object";

// Functions
typeof function () {} === "function";

// Undefined
typeof undefined === "undefined";

// Symbols
typeof Symbol() === "symbol";

// Booleans
typeof true === "boolean";

// Strings
typeof "apple" === "string";

// Numbers
typeof 20 === "number";
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof>
