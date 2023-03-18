---
title:  "[Typescript] Type Assertion "
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-18T08:06:00-05:00
---

In this post, it tells you about some of type assertion in type script.

# Type Assertion
Type Assertion is the type designation method that developers are confident about that type.

# Example

```typescript
let exam: any = 567; 
let test = <number> exam; 
```

```typescript
let exam: any = 789; 
let test = exam as number;
```


Thank you!

[Reference]
* kschoi : <https://kschoi.github.io/typescript/typescript/>