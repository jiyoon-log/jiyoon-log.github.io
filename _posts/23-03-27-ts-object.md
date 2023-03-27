---
title:  "[Typescript] Object"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-27T08:06:00-05:00
---

# Object

```typescript
let userA: { name: string, age: number } = {
  name: 'June',
  age: 567
};

let userB: { name: string, age: number } = {
  name: 'Jun',
  age: 333, 
  email: '123123@gmail.com' // Error
};
```

If you want to use agin and again, interface and type is better than object.


```typescript
interface User {
  name: string,
  age: number
}

let user1: User = {
  name: 'June',
  age: 123
}
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>