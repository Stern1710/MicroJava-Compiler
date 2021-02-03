# MicroJava Compiler #

A Compiler, written in Java, which compiles the MicroJava grammar into working Java Bytecode for the virtual machine. This program was written as the main part of the exercise track for the course Übersetzerbau by Hans-Peter Mössenböck, a part of the bachelor’s course for Computer Science at Johannes Kepler University (JKU), Linz.

<!-- TOC -->

- [MicroJava Compiler](#microjava-compiler)
  - [Used technologies](#used-technologies)
  - [Run the compiler](#run-the-compiler)
  - [Credits](#credits)
  - [Licence](#licence)

<!-- /TOC -->

## Used technologies ##

The compiler was written for the use with Java JDK 8 but should also work fine with any newer version (however not guaranteed).

## Run the compiler ##

Make sure you have Java installed and compile the project. To perform a compile run, run `Compiler` and pass as the first argument the mj-file you want to compile. The general form is as follows.

```text
java Compiler <path/to/.jm>
```

An example could be: `java Compiler /sample_microjava/StudentList.mj`

A typical output of the compilation process, if everything went fine, looks like the following:

```text
-----------------------------------
Parsing file sample_microjava/StudentList.mj
No errors.
```

There are already some code examples provided inside the `/sample_microjava` folder which you can use to validate whether you are using the program correctly. Be warned, some of them produce an error during compilation which is expected to show that the compiler is doing something and not just giving a plain output. An error could like the following:

```text
-----------------------------------
Parsing file sample_microjava/StudentList.mj
-- line 7 col 2: ; expected

1 errors.
```

## Credits ##

Even though the code was all written by myself, a big thanks and shoutout goes to fellow student Christopher Holzweber (<https://github.com/holzweber>), who was there for discussing the latest assignment, playing through different scenarios in the code and giving myself ideas on how to best implement my compiler.
PS: Did you know we and another colleague did a project together which is about image filtering based on audio files? Find it here on GitHub in Christoph’s public repository: <https://github.com/holzweber/ImageFiltering>

## Licence ##

This code is published under the GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007. This allows for private and commercial use, modification and distribution of the software as well as for patent use. In general, this software has neither warranty nor liability from my, the creators, side. If you use this source code, you also need to publish the code under the same licence. The copyright and the license notice must be preserved, and the source must be disclosed (published) when changes are made.
Please note that some files were made available by other authors and their respective copyright applies.
