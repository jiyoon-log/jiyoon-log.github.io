---
title:  "[Typescript] Generic"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-04-02T08:06:00-05:00
---

# Generic
The below example is from the reference page.


```typescript
function ex1<T>(arg: T, msg: T): T[] {
  return [arg, msg];
}

ex1<number>(35, 79);
ex1<string>('53', '97');
ex1<string | number>(35, '79');
ex1<number>(1, '2'); // Error
```

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>