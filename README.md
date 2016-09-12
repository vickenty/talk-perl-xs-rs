# Writing Perl extensions in Rust

[Video](https://www.youtube.com/watch?v=EZfm5rEnqBc)

[Slides](https://vickenty.github.io/talk-perl-xs-rs)

[Text version](talk.txt)

[Subject](https://github.com/vickenty/perl-xs)

## Abstract

Writing an extension module for Perl in C is tricky: it is easy to make a mistake that makes the interpreter catch fire and crash. XS API also adds its share of complexity.

Rust is a new programming language that has a strong focus on memory safety — preventing bugs that cause memory corruption and segfaults. It has thin runtime and can produce C-compatible shared libraries, which makes it suitable for embedding into other programs.

Rust expressive type system, macros, and standard library make it possible to abstract away many low-level details of XS API. The result is safer and more friendly API for extending Perl.
