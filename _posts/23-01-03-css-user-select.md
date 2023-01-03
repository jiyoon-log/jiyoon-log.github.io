---
title: "[CSS] user-select "

categories:
  - CSS
tags:
  - CSS
last_modified_at: 2023-01-03T08:06:00-05:00
---

In this post, it tells you about 'user-select'.

# user-select

The user-select property is to prevent text selection using drag or double-click in a browser.
It is used as prefix mostly.

```css
-webkit-user-select: none;
-moz-user-select: none;
-ms-user-select: none;
user-select: none;
```

# Syntax

```css
user-select: auto | all | none | text;
```

# user-select value

| <filter-function> values | Explanation                                               |
| ------------------------ | --------------------------------------------------------- |
| auto                     | default, if browser allows, then user can select the text |
| all                      | text can be selected by one click                         |
| none                     | no text selecting                                         |
| text                     | text selecting allow                                      |



Thanks.

[Reference]

- WEBISFREE: <https://webisfree.com/2018-10-31/css-%ED%85%8D%EC%8A%A4%ED%8A%B8-%EC%84%A0%ED%83%9D-%EB%93%9C%EB%9E%98%EA%B7%B8-%EC%84%A4%EC%A0%95-user-select-%ED%94%84%EB%A1%9C%ED%8D%BC%ED%8B%B0>
