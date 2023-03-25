---
title:  "[Typescript] tuple"
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-24T08:06:00-05:00
---

# Tuple

```typescript
let tuple : [string, number]
tuple = ['a', 1]
tuple = ['b', 2]
```

```typescript
let example : [string, number, boolean][]
example = [['a', 1, true], ['b', 2, true], ['c', 3, true]]
```

```typescript
let example : [30, string]
example = [30, 'a']
example = [2, 'b'] // Error
```


Thank you!

[Reference]
* Heropyblog : <https://heropy.blog/2020/01/27/typescript/>