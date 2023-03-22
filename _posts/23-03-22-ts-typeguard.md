---
title:  "[Typescript] Type Guard "
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-22T08:06:00-05:00
---

In this post, it tells you about some of type guard in type script.
Type guard allows you to narrow down the type of object in a condition statement.

# typeof
The operator determines the type of operand and returns it as a string.

```typescript
function test(arg: number|string) {
  if(typeof arg === 'number') {arg.substring(1)}
}
```

# instanceof
The operator can determine if the object to be determined belongs to a particular class.

```typescript
class Birthday {
  name: string
  day: number
}
class Holiday {
  country: string
}
function test(arg: Birthday | Holiday) {
  if(arg instanceof Birthday){
    console.log(arg.name)
  } else {
    console.log(arg.country)
  }
}
const birthday = new Birthday()
test(birthday)
```

Thank you!

[Reference]
* ChanBLOG : <https://chanhuiseok.github.io/posts/ts-2/>