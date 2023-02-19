---
title: "[Javascript] String.prototype.match()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-18T08:06:00-05:00
---

In this post, it tells you about some of String.prototype.match&#40;&#41;.

# String.prototype.match&#40;&#41;

It returns the result of matching the string which is matching with the regular expression in origin string.


# Syntax

```javascript
match(regexp)
```

## Parameters

- regexp &#58; Regular expression object for checking the stirng has the matching.


# Example
Example is from mdn page of String.prototype.match.

```javascript
const str = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz";
const regexp = /[A-E]/gi;
const matches = str.match(regexp);

console.log(matches);
// ['A', 'B', 'C', 'D', 'E', 'a', 'b', 'c', 'd', 'e']
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match>