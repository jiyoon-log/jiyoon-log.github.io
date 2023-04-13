---
title:  "[Typescript] Utility Types-Exclude"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-13T08:06:00-05:00
---

# Utility Types-Exclude

It returns a new type from type1 except type2.

```typescript
Exclude<TYPE1, TYPE2>
```

# Example

```typescript
type ex = number | string

const one = Exclude<ex, string> = 123
const two = Exclude<ex, string> = 'hello' //Error

```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>