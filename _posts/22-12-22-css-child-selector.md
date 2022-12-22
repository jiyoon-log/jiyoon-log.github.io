---
title:  "[CSS] CSS child selector is > "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-22T08:06:00-05:00
---

In this post, it tells you what is css child selector ">".

# CSS child selector

It uses in CSS.
">" means child selector. 
A child selector is a feature that specifies a tag that is located directly below the tag as a selector.

# Example 

```html
<div>
  <p>Hello!!</p>
  <h4>World!!</h4>
</div>
```

```css
div > p {
  color: blue;
}
```

# Result

![CSS-Child](/assets/img/CSS-Child.PNG)

"Hello" color is been changed.

Because under the "div" tag, there is "p".

"p" is the child tag of "div".

Thanks

[Reference]
* dasima: <https://dasima.xyz/css-%EB%B6%80%EB%93%B1%ED%98%B8-%EA%B8%B0%ED%98%B8-%EC%9D%98%EB%AF%B8/>
