---
title: "[CSS] ::first-letter"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-17T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;first-letter'.

# &#58;&#58;first-letter

It is for applying style for the first letter of the first block.

# Example

```html
<p>Hello, how are you? I am fine. I hope you are fine too. Have a wonderful day!</p>
<p>My day was same as usual. How was your day? Tomorrow will be much better than today. </p>
```

```css
p {
  width: 200px;
  line-height: 1.5;
}

p::first-letter {
  color: purple;
  background-color: yellow;
  box-shadow: 4px 3px red;
  margin-right: 6px;
}
```

# Result

![css-first-letter-ex](/assets/img/css-first-letter-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/::first-letter>
