---
title: "[CSS] ::after"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-11T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;after'.

# &#58;&#58;after

It creates one pseudo element as the last child of the selected elements.

# Syntax

```css
a::after {
  content: "< Example";
}
```

# Example

```html
<div>
  <ul>
    <li id="red">Strawberry is delicious.</li>
    <li id="blue">Sea is blue.</li>
  </ul>
</div>
```

```css
#red::after {
  content: " < Really!";
  color: red;
}

#blue::after {
  content: " I love it!";
  color: blue;
  background-color: yellow;
  border-color: brown;
  border-style: dotted;
}
```

# Result

![css-after-ex](/assets/img/css-after-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/CSS/::after>
