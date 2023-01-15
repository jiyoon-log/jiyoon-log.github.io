---
title: "[CSS] ::placeholder"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-14T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;placeholder'.

# &#58;&#58;placeholder

It workers for 'input' and 'textarea'.
It means for the placeholder text.

# Example

```html
<label for="NickName">Your nickname:</label><br>
<input placeholder="Any nickname is good!">
```

```css
input::placeholder {
  color: lightblue;
  font-size: 1em;
  font-style: italic;
}
```

# Result

![css-placeholder-ex](/assets/img/css-placeholder-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder>
