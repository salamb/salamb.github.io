---
layout: post
title:  "First Post, C#  "
date:   2021-02-05 -0500
categories: C# Interpreter
---

C# may be compiled but it actually runs in a VM similar to java.
Languages such as C# and F# are compiled by there respective compilers to
Intermediate Language(**IL**) code. The IL code is also known as managed code.
The VM then executes the IL code. The VM that executes the compiled code is
called the Common Language Runtime**(CLR)**.
Some things worth knowing about CLR include:

- The CLR can run code written in other managed languages ( IronPython C++/Cli etc.)
- If the CLR determines that there could be a benefit it will compile portions of the IL code to native code in real-time
using the Just in Time compiler (**JIT**).
- The CLR handles garbage collection



![Eye-Candy](/images/Csharp.jpg)
