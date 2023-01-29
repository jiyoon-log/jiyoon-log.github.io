---
title: "[CSS] :focus"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-29T08:06:00-05:00
---

In this post, it tells you about some of '	&#58;focus'.

# &#58;focus

The '	&#58;focus' is recognizing the focused elements.
It usually works when the user click or tab the elements.

# Syntax

```css
input:focus {
  color: gray;
}
```

# Example

```html
<label>First name: <input type="text" name="first_name" placeholder="Write the first name"/></label><br />
<label>Last name: <input type="text" name="last_name" placeholder="Write the last name"/></label>
```

```css
label {color: darkblue}
input:focus{
  background: lightblue;
  color: brown;
}
```

# Result

![css-focus-ex](/assets/img/css-focus-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/CSS/:focus>
