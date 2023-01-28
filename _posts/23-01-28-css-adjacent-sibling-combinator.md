---
title: "[CSS] Adjacent sibling combinator"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-28T08:06:00-05:00
---

In this post, it tells you about some of 'adjacent sibling combinator'.

# Adjacent sibling combinator

The 'Adjacent sibling combinator' combinator selects only sibling elements that are located immediately after the previously specified element.text decoration color.

# Syntax

```css
former_element + target_element { style properties }
```

# Example

```html
<h1>Hello</h1>
<h2>Hi</h2>
<h3>How are you</h3>
<h4>I am fine</h4>
```

```css
h1 + h2 {
  color: lime;
  text-decoration: green wavy underline;
}
h3 + h4 {
  color: lightblue;
  text-decoration: blue wavy underline;
}
```

# Result

![css-adjacent-sibling-ex](/assets/img/css-adjacent-sibling-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/ko/docs/Web/CSS/Adjacent_sibling_combinator>
