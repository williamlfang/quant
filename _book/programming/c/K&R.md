# K&R: The C Programming Language

“The C Programming Language” 是计算机编程的经典之作，别名 `K&R`。

这是一本简短精悍的书籍，介绍了 `C` 语言的编程核心、ANSI 规范、编译原理等诸多方面的内容。现在很难想象这本不足 200 页的小书尽然能够放得下这么多的内容，可以说是提纲挈领、言简意垓。尤其是附录A部分，只是简要介绍了 `C` 的编译原理，区区几页纸张就足以为后人编写各式不同的编译器提供指引。

根据我対本书的理解，把整本书籍分成四部分

-   第一部分：简单介绍 `C`，重点在于说明为何要把 `C` 设计成如此简要。一方面，是受到当时程序运行的硬件条件限制，最早 K.Tompson 和 D.Richie 是在 PDP-7、PDP-11 上面实现了 Unix 操作系统，然后在决定设计一款与这个 Unix 操作系统配套的编程语言，这必要要求新语言一定要足够精简以适应操作系统対性能的极致要求；另一方面，「小而美」是当时学术领域的一个普遍认可的观念，即根据「奥卡姆」定律：如无必要，请勿增添。因此，我们现在看得，`C` 语言最核心的内容其实很少，关键词不到 30 个，都是基本上达到了高级编程语言能够触摸的「底层地板」，但通过一定的设计之后，由这些命令组成的程序却又有着强大的能够，既能够实现対底层硬件（指针是 `C` 语言的核心，即变量在内存的地址）的直接操控，又能提供简洁明确的逻辑范式。
    -   Chapter 0: Introduction
        -   C is a general-purpose programming language。`C` 是一个通用的编程语言，既能够用于编写操作系统这类高难度的「程序」，也提供了一套开发高级程序的工具。
    -   Chapter 1: A Tutorial Introduction
-   第二部分：介绍 `C` 编程语言的核心。
    -   Chapter 2: Type, Operators, and Expression
    -   Chapter 3: Control Flow
    -   Chapter 4: Functions and Program Structure
    -   Chapter 5: Pointers and Arrays
    -   Chapter 6 Structures
-   第三部分：介绍标准库
    -   Chapter 7: Input and Output
    -   Chapter 8: The Unix System Interface
-   第四部分：附录
    -   Appendix A: Reference Manual
    -   Appendix B: Standard Library

