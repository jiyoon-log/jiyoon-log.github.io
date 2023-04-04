---
title:  "[Typescript] Conditional Types"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-04T08:06:00-05:00
---

# Conditional Types


```typescript
interface Birthday<T extends boolean> {
  name: string,
  date: T extends true ? string : number, 
  isString: T
}

const birthdate: Birthday<false> = {
  name: 'hihihi',
  age: 12, // Number
  isString: false
}
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>