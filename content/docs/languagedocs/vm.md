---
title: "Virtual Machine"
date: 2021-03-29T11:40:34+05:30
draft: true
---

[Mutant](https://github.com/gaurav-gogia/mutant) Language makes use of a virtual machine, known as "Mutant Virtual Machine" or MVM. This virtual machine makes sure that your program runs in **YOUR** machine. It has been tested on Linux, macOS, & Windows. Although, it should also work on Android, FreeBSD and essentially any platform/architecture that is supported natively by [Go Programming Language](https://golang.org).

This virtual machine is run everytime it has to run compiled `mu` files or whenever the user decides to run their programs through [REPL](/docs/languagedocs/repl)