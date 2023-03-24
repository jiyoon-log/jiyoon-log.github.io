---
title:  "[Typescript] indexed access types"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-23T08:06:00-05:00
---

# Indexed access types
```typescript
type Birthday = { day: number; name: string; age: number;};
type Age = Birthday["age"];
```

Thank you!

[Reference]
* ChanBLOG : <https://www.typescriptlang.org/docs/handbook/2/indexed-access-types.html>