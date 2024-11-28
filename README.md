**If you need a nice ODBC C++ Wrapper check [nanodbc](https://github.com/nanodbc/nanodbc)! Nanodbc is a fork to the now un-maintained TinyODBC with many more features!**

This project is left here for archive purposes.

----

### Uhhh, another OSS, what is this now?

TinyODBC is a C++ Wrapper around ODBC C API. That's all! Nothing more, nothing less! If you want a complete list of features check current status

### There is an official ODBC API for C! Why should I use this one?

Using ODBC C API produces quite "ugly" code and it is not object oriented! TinyODBC wraps ODBC C API and provides a C++ API that is Object Oriented, cleaner, easier to learn and takes advantage of many C++ techniques.

### Hmm, I got the point, but how can I install this?

As the title says TinyODBC is TINY! It consists of two source files, we could provide binaries but because of the size of the project you can just drop-in the sources to your project.

**Drop-in** means that you copy those two files in the directory of your project and include them for compiling in your IDE(Visual Studio, Code-Blocks, Eclipse etc) or command-line build system(Makefiles, cmake).

### Ok, I added, erm how do I use it

There is **online documentation**!

* [Introduction](docs/html/index.html)
* [API Reference](docs/html/annotated.html)
* [Examples](examples)