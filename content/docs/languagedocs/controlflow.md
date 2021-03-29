---
title: "Control Flow"
date: 2021-03-29T01:02:41+05:30
draft: true
---

[Mutant](https://github.com/gaurav-gogia/mutant) supports simple conditions and branching through if/else statements. Let's see them in action in below examples:

###### Example 1
```js
if(1 == 1) {
    puts("yes");
}
```

###### Example 2
```js
if(1 == 2) {
    puts("yes");
} else {
    puts("no");
}
```

###### Example 3
```js
if(1 == 2) {
    puts("yes");
} if(1 == 3) {
    puts("yes 3");
} else {
    puts("no");
}
```