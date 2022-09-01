---
title:  "[Javascript] how to use 'split'method"

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2022-09-01T08:06:00-05:00
---

In this post, it shows how to use 'split'. 

The string is divided based on the string received as a factor of split.

And the split string is returned in an array.

I used the three factors (blank, nothing, "").


# Using blank for split


[Example]
```javascript
const str = "Hello This is test. Bye";
const str2 = str.split(" ");

document.write(str2);
```

The 'str' is divided by the " ".

The each split string is return into arr2. 

[Result]
```
Hello,This,is,test.,Bye
```


# Using nothing for split

[Example]
```javascript
const str = "Hello This is test. Bye";
const str2 = str.split();

document.write(str2);

```

There is no factor of split. 
Therefore, there is no split.


[Result]
```
Hello This is test. Bye
```


# Using "" for split

[Example]
```javascript
const str = "Hello This is test. Bye";
const str2 = str.split("");

document.write(str2);

```

There is "" factor in the split. 
Therefore, the result shows the each characters. 


[Result]
```
H,e,l,l,o, ,T,h,i,s, ,i,s, ,t,e,s,t,., ,B,y,e
```

Thanks

[Reference]
* w3schools: <https://velog.io/@citron03/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-split-%EC%82%AC%EC%9A%A9-%EC%A0%95%EA%B7%9C%ED%91%9C%ED%98%84%EC%8B%9D>