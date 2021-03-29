---
title: "Getting Started"
date: 2021-03-29T01:02:05+05:30
draft: true
---

#### Install
Install the latest build by going through our [install](/docs/languagedocs/install/) section.

#### REPL
Run following command to ensure that mutant has been installed successfully
```bash
mutant
```

---

If it is installed correctly, then you should be able to see a similar screen:
![Home Page](/images/repl.png)

---

To run the age old "Hello, World" program, use following code snippet following image should be your output:
```bash
puts("Hello, World!");
```

![Home Page](/images/repl_hello.png)

#### Code through `mut` file
All your mutant source code files will have extension `mut`, this extension is used by the compiler to read the source code and generate the compiled bytecode file with `mu` extension.