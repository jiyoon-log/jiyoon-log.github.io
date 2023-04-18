---
title:  "[Typescript] Utility Types-ReturnType"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-18T08:06:00-05:00
---

# Utility Types-ReturnType

It returns function's return type into the new type.

```typescript
ReturnType<TYPE>
```
# Example

```typescript
function Days(str: string) {
  return str;
}

const ex1: ReturnType<typeof Days> = 'Birthday';
const ex2: ReturnType<typeof Days> = 1234; // Error
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>