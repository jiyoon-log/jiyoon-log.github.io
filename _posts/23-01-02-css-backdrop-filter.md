---
title: "[CSS] backdrop-filter "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-02T08:06:00-05:00
---

In this post, it tells you about 'backdrop-filter'.

# backdrop-filter

The backdrop-filter property sets the graphical effects like blurring, color shifting or others to the behind the area of property.

# backdrop-filter value

| <filter-function> values | Explanation                     |
| ------------------------ | ------------------------------- |
| none                     | no effect                       |
| blur(px)                 | blurring                        |
| brightness(%)            | light and darkness              |
| contrast(%)              | contrast of image               |
| drop-shadow()            | shadow of image                 |
| grayscale(%)             | grayscale of image              |
| hue-rotate(deg)          | colorscale of image             |
| invert(%)                | reverse an image                |
| opacity(%)               | transparency of image           |
| saturate(%)              | saturation of image             |
| sepia(%)                 | sepia effect of image           |
| url()                    | image path                      |
| inherit                  | inherit from the parent element |

# Syntax

```css
backdrop-filter: none | blur() | brightness() | contrast() | drop-shadow() |
  grayscale() | hue-rotate() | invert() | opacity() | sepia() | saturate();
```

# Example

```html
<div class="container">
  <div class="box">
    <p>backdrop-filter: none</p>
  </div>
</div>
<div class="container">
  <div class="box" id="blur">
    <p>backdrop-filter: blur(10px)</p>
  </div>
</div>
<div class="container">
  <div class="box" id="brightness">
    <p>backdrop-filter: brightness(50%)</p>
  </div>
</div>
<div class="container">
  <div class="box" id="grayscale">
    <p>backdrop-filter: grayscale(75%)</p>
  </div>
</div>
```

```css
.box {
  background-image: rgba(255, 255, 255, 0.3);
  text-align: center;
  line-height: 1;
  max-width: 50%;
  max-height: 50%;
  padding: 20px 40px;
  display: block;
}
#blur {
  -webkit-backdrop-filter: blur(10px);
  backdrop-filter: blur(30px);
}
#brightness {
  -webkit-backdrop-filter: brightness(50%);
  backdrop-filter: brightness(50%);
}
#grayscale {
  -webkit-backdrop-filter: grayscale(75%);
  backdrop-filter: grayscale(75%);
}


body {
  display: flex;
}

.container {
  background-image: url("./img/free_image.jpg");
  width: 400px;
  height: 200px;
  align-items: center;
  justify-content: center;
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  margin-right: 10px;
}
```

# Result

![backdrop-filter-ex](/assets/img/backdrop-filter-ex.PNG)

Thanks.

[Reference]

- mdn web docs: <https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter>
- WEBSTORYBOY : <https://webzz.tistory.com/504>
- pic is from <https://stock.adobe.com/kr/free>
