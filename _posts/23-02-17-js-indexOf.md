---
title: "[Javascript] String.prototype.indexOf()"
excerpt: ""

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2023-02-17T08:06:00-05:00
---

In this post, it tells you about some of String.prototype.indexOf&#40;&#41;.

# String.prototype.indexOf&#40;&#41;

It returns the first place of the given string starting index.


# Syntax

```javascript
indexOf(searchString)
indexOf(searchString, position)
```

## Parameters

- seachString &#58; Substring to search for.
- position &#58; It returns the first index of the SearchString occuring. But if the position index is smaller then given index, it returns &#45;1.

# Example

```javascript
const str = "Hello new world";

console.log(str.indexOf("w")); // 8
console.log(str.indexOf("new")); // 6
```

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf>
