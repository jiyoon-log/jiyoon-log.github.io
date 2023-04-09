---
title:  "[Typescript] Utility Types-Required"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-08T08:06:00-05:00
---

# Utility Types-Required

It returns new type (interface) with all properties of TYPE changed to mandatory.

```typescript
Required<TYPE>
```

# Example

```typescript
interface Days {
  name?: string,
  date?: number
}

const birthday: Days = {
  name: 'Apple'
}
const holiday: Required<Days> = {  // error
  name: 'Banana'
}
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>