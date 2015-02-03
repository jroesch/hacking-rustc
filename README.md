Hacking Rustc
=======

A hackers guide to the Rust compiler.

This is something I have started assembling as a guide to introduce a new hacker to the Rust compiler. This is mostly
pitched at people who have experience working on a compiler but may be interesting to all people.

It seems a shame that the language's libraries and tools have such great documentation but there is no definitive guide to working on Rustc itself.

This is my attempt to rectify that as much as possible and clarify how the pieces of the compiler work together, and the important functionality in each. This is also is a great activity that helps both with my research and efforts to improve the compiler internals.

## Overview 

We will begin with a high level tour of the compiler, and drill down in to the specifics in turn.

* Building Rust
* syntax
* rustc
* rustc_driver
* rustc_typeck
* rusct_borrowck
* rustc_resolve
* rustc_trans



