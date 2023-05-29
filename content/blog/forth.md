+++
title = "Forth"

description = "Go Forth, and *"
date = "2023-05-29"
+++
# Forth

### A language that could have been

Forth was created by Charles H. Moore in 1970. It's a thin, stack-machine
shaped veneer over assembly, and it writes itself.

Originally implemented as a series of macros, the self-expanding language is
what I *wish* Lisp could be (though more types and safety could be nice too).

The core of Forth is the colon definition. It looks like this:

```forth
: hello
    ." hello world" ;
```

Forth also has a powerful macro system, similar to (and maybe inspired/inspired by) Lisp:

```forth
: hello2
    s" hello world!" ' type ;
```
