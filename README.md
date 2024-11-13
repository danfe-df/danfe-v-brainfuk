# BRAINFUCK Esolang Interpreter

Brainfuck esolang interpreter written completely in [Danfe](https://danfe.sariashgautam.com.np)

Brainfuck was invented by Urban Müller in `1993`, in an attempt to make a language for which he could write the smallest possible compiler for the Amiga OS, version 2.0. He managed to write a 240-byte compiler. The language was inspired by [FALSE](https://esolangs.org/wiki/FALSE), which had a 1024-byte compiler. Müller chose to name the language brainfuck (with the initial letter in lower case, although it is now often capitalised).

[Wiki](https://esolangs.org/wiki/Brainfuck)


To use this interpreter you have to `write` the program in a `file` and run it like the example given bellow:

``` sh
danfe run ./main.df ./example_bf_programs/helloworld.bf
```

``` md
# Output
Hello World!
```