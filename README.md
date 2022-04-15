# Programming Language Wish List

I use Python since 2001 and it works fine for most of my use-cases.

Nevertheless there are some things about Golang which are nice.

Instead of comparing Python with Golang I decided to ask myself:

Thomas, what is your wish list for a programming language?

# Wasm

The language should be able to be compiled to [WebAssembly](https://webassembly.org/)

This way you can run your code in modern browsers.


# Energy Consumption

I don't want to burn the planet. My small applications don't run at scale, so it does
not matter much.

Nevertheless I would like my programms to be fast, efficient and use little energy.

Here you can read that Python is not efficient [Sustainability with Rust](https://aws.amazon.com/de/blogs/opensource/sustainability-with-rust/)

Dynamic typing is nice, but overall I don't need it. I can work with a staticaly typed language,
since this would reduce energy consumption.

# Easy to read

I think Python code is often beautiful. 

Classes use CamelCase and uppercase, and methods use snake_case and lower case.

That's one thing I don't like about golang. 

# No pointers

The great thing about Python: You don't need to worry about pointers. It just works.

This semantic is part of my wish list.

# name2type mapping

The language should support a [name2type mapping](https://github.com/guettli/python-name2type-mapping).

This can help to keep the source code clean an easier to read for humans.

# Packaging should be part of the core project

In Python packaging is not part of the core. There are several ways to package and install
code (pip, conda, ...).

It would be nice if there was one way to package and install the code.

# Template Literals

Python [f-strings](https://docs.python.org/3/tutorial/inputoutput.html#formatted-string-literals) are nice,
but [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals) could
be even better.

For example auto-escaping all arguments would be great.

More about this: [Template Literals to Python](https://github.com/guettli/peps/blob/master/pep-9999.rst)

# html templating in the standard library

Go has a great [template/html](https://pkg.go.dev/html/template) library.

I would love to have this: Strings get quoted according to their context.

Combined with f-string like template-literals this would be heaven to
create HTML inside code ([Locality of Behaviour](https://htmx.org/essays/locality-of-behaviour/).

# Async transparent

I don't want to type `async` and `await` again and again.

I think there is a way to create a async-transparent language.

Up to now the only language I know which is async-transparent is [hyperscript](https://hyperscript.org/)

# Garbage Collection

I know that Rust is faster than golang, but nevertheless garbage collection is on my wish list.

I don't want to allocate and free memory.

# gRPC Integration

There should be a gRPC integration

# OOP

I think object-oriented-programming is overrated. Nevertheless I don't want to miss it.

## Explicit parent constructor

I like the explicit way you need to call the parent-constructur in Python.

It is perfectly fine to write this one line in the constructor of your class.



# Feedback is welcome

Please tell me your thoughts. The prefered way is to open an issue.


# More

[Thomas WOL: Working out Loud](https://github.com/guettli/wol)

