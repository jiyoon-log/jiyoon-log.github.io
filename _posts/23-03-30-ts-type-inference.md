---
title:  "[Typescript] Type Inference"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-30T08:06:00-05:00
---

# Type Inference

If there are no type definitions, then typescript inference the types of the objects.

```typescript
let string = 'hello'
string = 123 // Error
```

In the above example, typescript inference that the string type is string.
That's why the error message come out when the number 123 is assined.

The typescript deduces the type as follows.

- initializaed variable
- parameters with default values
- function with return value 

Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>