---
title:  "[Typescript] Utility Types-NonNullable"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-15T08:06:00-05:00
---

# Utility Types-NonNullable

It returns a new type from union type except for null and undefined.

```typescript
NonNullable<TYPE>
```

# Example

```typescript
type ex1 = number | string | null | undefined

const one: NonNullable<ex1> = null // Error
const two: ex1 = undefined 

```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>