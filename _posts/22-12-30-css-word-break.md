---
title:  "[CSS] word-break "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2022-12-31T08:06:00-05:00
---

In this post, it tells you about word-break.

# word-break

It is one of the display properties of the CSS, which determine how the line breaks.

- word-break: normal; // the default line break rule
- word-break: break-all; // line break by text (except Korea, Japanese, Chinese text)
- word-break: keep-all; // line break by word 
- word-break: break-word; // act like "word-break: normal" and "overflow-wrap:anywhere" 


# Example

```html
	<div class="box-container">
		<div class="box" style="word-break:normal">
			<h1>normal</h1>working together to keep the Internet alive and accessible, so people worldwide can be informed
			contributors and creators of the Web. We believe this act of human collaboration across an open platform is
			essential to individual growth and our collective future. 전 세계 사람들이 웹의 기여자와 작성자에게 정보를 제공할 수 있도록 인터넷을 활성화하고 접근할 수
			있도록 함께 노력합니다. 우리는 개방형 플랫폼을 통한 인간의 협력 행위가 개인의 성장과 우리의 집단적 미래에 필수적이라고 믿는다.
		</div>
		<div class="box" style="word-break:break-all">
			<h1>break-all</h1>working together to keep the Internet alive and accessible, so people worldwide can be informed
			contributors and creators of the Web. We believe this act of human collaboration across an open platform is
			essential to individual growth and our collective future. 전 세계 사람들이 웹의 기여자와 작성자에게 정보를 제공할 수 있도록 인터넷을 활성화하고 접근할 수
			있도록 함께 노력합니다. 우리는 개방형 플랫폼을 통한 인간의 협력 행위가 개인의 성장과 우리의 집단적 미래에 필수적이라고 믿는다.
		</div>
		<div class="box" style="word-break:keep-all">
			<h1>keep-all</h1>working together to keep the Internet alive and accessible, so people worldwide can be informed
			contributors and creators of the Web. We believe this act of human collaboration across an open platform is
			essential to individual growth and our collective future. 전 세계 사람들이 웹의 기여자와 작성자에게 정보를 제공할 수 있도록 인터넷을 활성화하고 접근할 수
			있도록 함께 노력합니다. 우리는 개방형 플랫폼을 통한 인간의 협력 행위가 개인의 성장과 우리의 집단적 미래에 필수적이라고 믿는다.
		</div>
		<div class="box" style="word-break:break-word">
			<h1>break-word</h1>working together to keep the Internet alive and accessible, so people worldwide can be informed
			contributors and creators of the Web. We believe this act of human collaboration across an open platform is
			essential to individual growth and our collective future. 전 세계 사람들이 웹의 기여자와 작성자에게 정보를 제공할 수 있도록 인터넷을 활성화하고 접근할 수
			있도록 함께 노력합니다. 우리는 개방형 플랫폼을 통한 인간의 협력 행위가 개인의 성장과 우리의 집단적 미래에 필수적이라고 믿는다.
		</div>
	</div>
```

```css
.box-container {
  display: flex;
}
.box {
  width: 400px;
  height: 300px;
  border: 2px solid darkblue;
}
```
![word-break-ex](/assets/img/word-break-ex.PNG)


Thanks.

[Reference]
* mdn web docs: <https://developer.mozilla.org/ko/docs/Web/CSS/word-break>
* Mozilla (for example text)

