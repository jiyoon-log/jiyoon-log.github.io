---
title:  "[Typescript] Constraints"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-03T08:06:00-05:00
---

# Constraints


```typescript
interface stan<T extends string | number> {
  name: string,
  value: T
}

const ex1: stan<string> = {
  name: 'Example A',
  value: 'Hi'
}
const ex2: stan<number> = {
  name: 'Exmple B',
  value: 7
}
const ex3: stan<boolean> = { // Error
  name: 'Data C',
  value: true
}
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>