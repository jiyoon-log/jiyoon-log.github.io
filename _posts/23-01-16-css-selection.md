---
title: "[CSS] ::selection"
excerpt: ""

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-16T08:06:00-05:00
---

In this post, it tells you about some of '&#58;&#58;selection'.

# &#58;&#58;selection

It is for applying styles when the user highlights.

# Example

```html
<div class="box">
	<ul>
		<li id="red">Red is red.</li>
		<li id="blue">Blue is blue.</li>
	</ul>
</div>
```

```css
.box {
  background-color: black;
}
li {
  color: white;
}
#red::selection {
  color: red;
  background-color: gold;
}
#blue::selection {
  color: blue;
  background-color: lightblue;
}
```

# Result

![css-selection-ex](/assets/img/css-selection-ex.PNG)

Thank you!

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/::selection>
