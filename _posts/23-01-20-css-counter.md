---
title: "[CSS] counter()"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-20T08:06:00-05:00
---

In this post, it tells you about some of 'counter()'.

# counter()

It is for returning counter's value if it is string.

# Example

```html
<ol class="fruits">
  <li>Apple</li>
  <li>Banana</li>
  <li>Melon</li>
</ol>
```

```css
body {background-color: lightpink;}
.fruits li {counter-increment: listCounter;}
.fruits li::marker {content: counter(listCounter, decimal) ") ";}
```

# Result

![css-counter-ex](/assets/img/css-counter-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/counter>
