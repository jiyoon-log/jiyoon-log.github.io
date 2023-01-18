---
title: "[CSS] ::first-line"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-18T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;first-line'.

# &#58;&#58;first-line

It is for applying style for the first line of the first block.

# Example

```html
<p>Hello, how are you? <br>I am fine. I hope you are fine too. Have a wonderful day!</p>
<p>My day was same as usual. How was your day? Tomorrow will be much better than today. </p>
```

```css
p {
  width: 200px;
  line-height: 1.5;
}

p::first-line {
  color: purple;
  background-color: yellow;
  box-shadow: 4px 3px red;
  margin-right: 6px;
}
```

# Result

![css-first-line-ex](/assets/img/css-first-line-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/::first-line>
