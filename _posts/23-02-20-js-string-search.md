---
title: "[Javascript] String.prototype.search()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-20T08:06:00-05:00
---

In this post, it tells you about some of String.prototype.search&#40;&#41;.

# String.prototype.search&#40;&#41;

It searchs for a match between a regular expression and the String object.


# Syntax

```javascript
search(regexp)
```

## Parameters

- regexp &#58; regular expression for searching string or object


# Example
Example is from mdn page of String.prototype.search.

```javascript
const str = "hey JudE";
const re = /[A-Z]/;
const reDot = /[.]/;
console.log(str.search(re)); // returns 4, which is the index of the first capital letter "J"
console.log(str.search(reDot)); // returns -1 cannot find '.' dot punctuation
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/search>
