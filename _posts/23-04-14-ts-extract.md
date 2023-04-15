---
title:  "[Typescript] Utility Types-Extract"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-14T08:06:00-05:00
---

# Utility Types-Extract

It returns a new type that extracts from type2 in type1.

```typescript
Extract<TYPE1, TYPE2>
```

# Example

```typescript
type ex1 = number | string
type ex2 = number | boolean

const one: Extract<ex1, ex2> = 123
const two: Extract<ex1, ex2> = 'hello' //Error

```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>