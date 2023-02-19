---
title: "[Javascript] String.prototype.replace()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-19T08:06:00-05:00
---

In this post, it tells you about some of String.prototype.replace&#40;&#41;.

# String.prototype.replace&#40;&#41;

It returns a new string with specific position in the string is been changed with pattern. 


# Syntax

```javascript
replace(pattern, replacement)
```

## Parameters

- pattern &#58; String or Object
- replacement &#58; can be string or function. 


# Example
Example is from mdn page of String.prototype..

```javascript
const str = "Twas the night before Xmas...";
const newstr = str.replace(/xmas/i, "Christmas");
console.log(newstr); // Twas the night before Christmas...
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace>
