---
title:  "[Javascript] how to use 'while'"

categories:
  - Javascript
tags:
  - Javascript
last_modified_at: 2022-08-25T08:06:00-05:00
---

In this post, it shows how to use 'while'. 


# while

This while loop is executed over and over if the condition is true. 

[Example]
```javascript
let i = 0;
while (i < 10) {
  document.write(i+" : ");
  i++;
}
```

- i < 10 : conditional expression that for startement operation.
- document.write(i+" : "); i++; : code executed while the statement is operating


[Result]
```
0 : 1 : 2 : 3 : 4 : 5 : 6 : 7 : 8 : 9 :
```

# do/while

This do/while loop has to be executed at least once. 
Even if the condition is not true because the condition is not tested.
That's the difference between just while loop and do/while loop. 

[Example]
```javascript
let i = 0;
do {
document.write(i+" > ");
i++;
}
while (i<10);
```
- i< 0 : conditional expression that for startement operation.


[Result]
```
0 > 1 > 2 > 3 > 4 > 5 > 6 > 7 > 8 > 9 >
```

Thanks

[Reference]
* w3schools: <https://www.w3schools.com/js/js_loop_while.asp>