---
title:  "[Typescript] Interface & Type "
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-21T08:06:00-05:00
---

In this post, it tells you about some of interface and type in type script.

The below interface and type example are same function but different way.

# Interface
This example is from reference page.

```typescript
interface Animal {
  name: string
}

interface Bear extends Animal {
  honey: boolean
}

const bear = getBear() 
bear.name
bear.honey
```

# Type 
This example is from reference page.

```typescript
type Animal = {
  name: string
}

type Bear = Animal & { 
  honey: boolean 
}

const bear = getBear();
bear.name;
bear.honey;
```


Thank you!

[Reference]
* typescript : <https://www.typescriptlang.org/docs/handbook/2/everyday-types.html>