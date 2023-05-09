---
title: "[Error] npm install error"
excerpt: ""

categories:
  - Error
tags:
  - Error
last_modified_at: 2023-05-09T08:06:00-05:00
---

In this post, it tells you about solution that works for my case.
I hope it works for you too.

# Error

Error message was like below.

```
Cannot read properties of null (reading 'pickAlgorithm')
```

So I did below solution.

```
npm cache clear --force
npm install
```

Then, it worked.

[Reference]

- stackoverflow: <https://stackoverflow.com/questions/69567381/getting-cannot-read-property-pickalgorithm-of-null-error-in-react-native>
