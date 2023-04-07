---
title:  "[Typescript] Utility Types-Partial"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-05T08:06:00-05:00
---

# Utility Types-Partial

It returns a new type with all properties of the TYPE changed to optional.

```typescript
Partial<TYPE>
```

# Example

```typescript
interface Days {
  name: string,
  date: number
}

const birthday: Days = { 
  name: 'baby'
}
const holiday: Partial<Days> = {
  name: 'Easter'
}
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>