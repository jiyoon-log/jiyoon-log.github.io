---
title:  "[Typescript] keyof"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-31T08:06:00-05:00
---

# keyof


```typescript
interface Person {
  man: 'A',
  woman: 'B'
}
let person: keyof Person
person = 'man'
person = 'boy' // error
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>