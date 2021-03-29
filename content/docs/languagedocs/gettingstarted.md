---
title: "Getting Started"
date: 2021-03-29T01:02:05+05:30
draft: true
---

#### Install
Install the latest build by going through our [install](/docs/languagedocs/install/) section.

#### REPL
Run following command to ensure that [mutant](https://github.com/gaurav-gogia/mutant) has been installed successfully
```bash
mutant
```

---

If it is installed correctly, then you should be able to see a similar screen:
![Mutant REPL](/images/repl.png)

---

To run the age old "Hello, World" program, use following code snippet following image should be your output:
```bash
puts("Hello, World!");
```

![Mutant REPL](/images/repl_hello.png)

#### Code through `mut` file
All your mutant source code files will have extension `mut`, this extension is used by the compiler to read the source code and generate the compiled bytecode file with `mu` extension.

1. Create a file named `code.mut` in any directory of your choice
2. Write some [mutant](https://github.com/gaurav-gogia/mutant) code in in that file using the IDE of your choice
3. Run `mutant code.mut` to generate the compiled `mu` file with the same name in same directory
4. Run `mutant code.mu` to run your compiled code