---
title: "[CSS] ::marker"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-14T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;marker'.

# &#58;&#58;marker

It workers for 'li' and 'summary'.
It makes user select the marker.

# Example

```html
<ul>
  <li>Yellow</li>
  <li>Blue</li>
</ul>
```

```css
ul li::marker {
  color: purple;
  font-size: 2em;
}
```

# Result

![css-marker-ex](/assets/img/css-marker-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/::marker>
