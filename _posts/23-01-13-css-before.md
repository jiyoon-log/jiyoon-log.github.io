---
title: "[CSS] ::before"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-13T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;before'.

# &#58;&#58;before

It creates one pseudo element as the first child of the selected elements.

# Syntax

```css
a::before {
  content: "Example >";
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
body {background-color: lightblue;}
#red::before {
  content: " Really! > ";
  color: red;
}

#blue::before {
  content: " I love it! ";
  color: white;
  background-color: brown;
  border-color: yellow;
  border-style: dotted;
}
```

# Result

![css-before-ex](/assets/img/css-before-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/CSS/::before>
