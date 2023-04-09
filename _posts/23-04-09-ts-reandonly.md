---
title:  "[Typescript] Utility Types-ReadOnly"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-09T08:06:00-05:00
---

# Utility Types-ReadOnly

It returns new type with changing properties into readonly.

```typescript
Readonly<TYPE>
```

# Example

```typescript
interface Days {
  name: string,
  date: number
}

const birthday: ReadOnly<Days> = {
  name: 'Apple'
}
birthday.name = 'Banana' // Error

```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>