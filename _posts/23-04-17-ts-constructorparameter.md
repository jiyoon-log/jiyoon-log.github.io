---
title:  "[Typescript] Utility Types-ConstructorParameter"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-16T08:06:00-05:00
---

# Utility Types-ConstructorParameter

It returns class's constructor parameters into the new tuple.

```typescript
ConstructorParameters<TYPE>
```
# Example

```typescript
class Days {
  constructor (public name: string, private date: number) {}
}

const birthday = new days('Jane', 23);
const ex1: ConstructorParameters<typeof Days> = ['Jane', 23];
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>