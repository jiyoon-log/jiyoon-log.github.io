---
title: "[Javascript] Object.prototype.isPrototypeOf()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-24T08:06:00-05:00
---

In this post, it tells you about some of Object.prototype.isPrototypeOf&#40;&#41;.

# Object.prototype.isPrototypeOf&#40;&#41;

It checks if an object exists in another object's prototype chain.


# Syntax

```javascript
isPrototypeOf(object)
```

## Parameter
- object : the prototype chain will be searched


# Example
Example is from mdn page of Object.prototype.isPrototypeOf&#40;&#41;.

```javascript
class Foo {}
class Bar extends Foo {}

const foo = new Foo();
const bar = new Bar();

// prototype chains:
// foo: Foo --> Object
// bar: Bar --> Foo --> Object
console.log(Bar.prototype.isPrototypeOf(foo)); // false
console.log(Foo.prototype.isPrototypeOf(bar)); // true
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/isPrototypeOf>
