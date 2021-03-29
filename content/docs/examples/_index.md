---
title: "Examples"
date: 2021-03-28T11:06:57+05:30
draft: false
weight: 3
---

Here is a list of some example [mutant](https://github.com/gaurav-gogia/mutant) programs to get your journey started:

1. Add two numbers:
```js
let sum = fn(n1, n2) {
    return n1 + n2;
};

putln("Lets add two numbers: ");

puts("Enter first number: ");
let num1 = gets("int");

puts("Enter second number: ");
let num2 = gets("int");

sum(num1, num2);
```

2. Print Fibonacci Series
```js
let fibonacci = fn(x) {
    if (x == 0) {
        return 0;
    } else {
        if (x == 1) {
            return 1;
        } else {
            fibonacci(x - 1) + fibonacci(x - 2);
        }
    }
};

fibonacci(10);
```