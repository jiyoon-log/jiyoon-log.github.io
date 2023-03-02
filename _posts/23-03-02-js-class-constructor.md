---
title: "[Javascript] Class constructor"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-03-02T08:06:00-05:00
---

In this post, it tells you about some of class constructor.

# Class constructor

It creates and initializing an object instance of that class.


# Syntax

```javascript
constructor() { /* … */ }
constructor(argument0) { /* … */ }
constructor(argument0, argument1) { /* … */ }
constructor(argument0, argument1, /* … ,*/ argumentN) { /* … */ }
```


# Example
Example is from mdn page of class constructor.

```javascript
class Person {
  constructor(name = "Apple") {
    this.name = name;
  }
  introduce() {
    console.log(`Hello, this is ${this.name}`);
  }
}

const person = new Person();
person.introduce(); // Hello, this is Apple
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor>
