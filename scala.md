Notes from David Venturi' course on Data Camp:

https://campus.datacamp.com/courses/introduction-to-scala/a-scalable-language?ex=1

"Scala" means staircase in Italian, the logo was also inspired by the staircase in which the language was born.

Scala stands for "**Sca**lable **La**nguage" (it is a *portmanteau* - a word blending the sounds and combining the meanings of two others).

What is Scala?

> Scala is a general-purpose programming language providing support for functional programming and a strong static type system. Designed to be concise, many of Scala's design decisions aimed to address criticisms of Java -- Wikipedia

Scala source code is intended to be compiled to Java bytecode, so that the resulting executable code runs on a Java virtual machine.

Scala is designed to growth with the demands of its users.

> To borrow an analogy from Eric Raymond's The Cathedral and the Bazaar. A cathedral is a building with rigid perfection, it takes a long time to build and rarely changes after being built. A bazaar, on the other hand, is flexible. It is adapted and extended often by the people working in it.

Scala is not a perfectly complete language. Everything is customisable to your program's requirement.

Scala is convenient in that the standard library has a set of predefined types, collections and control structures.

Yet is is flexible in that you can add types, collections, and control structure that feel like they are built-in to the language.

Your program will never out grow Scala. Apache Spark is written in Scala.

> Scala combines object-oriented and functional programming in one concise, high-level language. Scala's static types help avoid bugs in complex applications, and its JVM and JavaScript runtimes let you build high-performance systems with easy access to huge ecosystems of libraries. -- https://www.scala-lang.org/

It's this fusion between object-oriented and functional-programming that contributes most to the scalability of the language according to Martin Odersky (the cretor of Scala).

In Scala:

- Every value is an object
- Every operation is a method call

```scala
val sumA = 2 + 4

sumA: Int = 6
```

Behind the scenes Scala rewrites the method plus being called on the object 2

```scala
val sumA = 2. + (4)
```

Functions are first class values in Scala - you can pass them as arguments to other functions, return them from other functions, store them in variables, et cetera.

In functional programming, operations of a program should map input values to output values rather than change data in place. *Functions should not have side effects*

Scala is concise, often one tenth the size of Java programs.

Scala is high-level, you don't deal with "low-level" details of the computer running it.

Scala has an advanced static type system that reduces verbosity in your code and adds language flexibility.

Scala is compatible with pre-existing Java code.
