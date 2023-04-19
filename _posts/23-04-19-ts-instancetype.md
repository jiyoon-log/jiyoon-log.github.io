---
title:  "[Typescript] Utility Types-InstanceType"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-19T08:06:00-05:00
---

# Utility Types-InstanceType

It returns class typs's instance type.

```typescript
InstanceType<TYPE>
```
# Example

```typescript
class Days {
  constructor(public name: string) {}
}

const birthday: InstanceType<typeof Days> = new Days('Birthday');
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>