---
title: "[HTML] output"
excerpt: ""

categories:
  - HTML
tags:
  - HTML
last_modified_at: 2023-01-30T08:06:00-05:00
---

In this post, it tells you about some of 'output'.

# output

The 'ouput' is a container element that allows a website or app to insert the results of a calculation or user behavior.

# Example

```html
<form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
  <input type="range" id="b" name="b" value="50" /> +
  <input type="number" id="a" name="a" value="10" /> =
  <output name="result" for="a b">60</output>
</form>
```

# Result

![html-output-ex](/assets/img/html-output-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/HTML/Element/output>
