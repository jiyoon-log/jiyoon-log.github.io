---
title:  "[Typescript] Interface "
excerpt: ""

categories:
  - Typescript
tags:
  - Typescript
last_modified_at: 2023-03-20T08:06:00-05:00
---

In this post, it tells you about some of interface in type script.


# Example
This example is from reference page.

```typescript
interface LabeledValue {
  label: string;
}

function printLabel(labeledObj: LabeledValue) {
  console.log(labeledObj.label);
}

let myObj = { size: 10, label: "final" };
printLabel(myObj); // final
```


Thank you!

[Reference]
* typescript : <https://www.typescriptlang.org/docs/handbook/interfaces.html>