---
title:  "[Typescript] Type Declaration -2 "
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-17T08:06:00-05:00
---

In this post, it tells you about some of type decalation in typescript.

# object

```typescript
const obj: object = {}
```

# array

```typescript
let arr: number[] = [1, 2, 3]
```

# tuple

```typescript
let tuple1: [string, number]
tuple1 = ["hello", 10] // OK

let tuple2: [number, string]
tuple2 = [10, "hello"] // OK
```

# any

```typescript
let anything: any
anything = "hello"
anything = 20
anything = true
```

# void

```typescript
function write(): void {
	console.log("Hello");
}
```


Thank you!

[Reference]
* kschoi : <https://kschoi.github.io/typescript/typescript/>