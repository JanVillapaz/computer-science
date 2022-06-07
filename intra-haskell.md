# Haskell - Intra

Intro
-

Haskell is a purely functional language. It has been specially designed to handle symbolic computation and list processing applications. 

- **Functional programming:** Based on mathematical functions.
- **Examples of other functional programming paradigm:** Lisp, Python, Erlang, Racket, F#, Clojure, etc.
- In **conventional programming**, instructions are taken as a set of declarations in a specific syntax or format
- In **functional programming**, all the computation is considered as a combination of separate mathematical functions.

#### Few points why this language is special
- **Functional language:** In a conventional language, we instruct the compiler a series of tasks which is nothing but telling your computer “What to do” and “how to do?”. But in Haskell, we tell out computer “what it is?”.
- **Laziness:** Haskell is a lazy language. By lazy, we mean that Haskell won’t evaluate any expression without any reason. When the evaluation engine finds that an expression needs to be evaluated, then it creates a **thunk data structure** to collect all the required information for that specific evaluation and a pointer to that thunk data structure. The evaluation engine will start working only when it is required to evaluate that specific expression.
- **Thunk:** a subroutine used to inject a calculation into another subroutine.
- **Modularity:** A Haskell application is nothing but a series of functions. We can say that a Haskell application is a collection of numerous small Haskell applications.
- **Statically Typed:** In conventional programming language, we need to define a series of variables along with their type. In contrast, Haskell is a type of interference language. By the term, type interference language, we mean the Haskell compiler is intelligent enough to figure out the type of the variable declared, hence we need not explicitly mention the type of the variable used.
- **Maintainability:** Haskell applications are modular and hence, it is very easy and cost-effective to maintain them.

Functional programs are more concurrent, and they follow parallelism in execution to provide more accurate and better performance. Haskell is no exception; it has been developed in a way to handle multithreading effectively.

Hello World
-
It is a simple example to demonstrate the dynamism of Haskell. All we need is one line to print “Hello World” on the console.

```haskell
Main = putStrLn “ Hello World”
```

Once the Haskell compiler encounters the above piece of code, it promptly yields the following output -
```console
Hello World
```

Basic Data Models
-

Haskell is a purely functional programming language, hence it is much more interactive and intelligent than other programming languages. In this part, we will learn about the basic data models which are actually predefined or somehow intelligently decoded into the computer memory.

#### Numbers
Haskell is intelligent enough to decode that some numbers are in fact numbers. Therefore, you need not mention its type externally as we usually do in the case of other programming languages. As per example, we can go to our prelude command prompt and jun run "2 + 2" and hit enter. You get "4".

We passed two numbers as arguments to the GHCI compiler without predefining their type, but the compiler easily decoded that the to entries as numbers.

#### Characters
Like numbers, Haskell can intelligently identify a character given in as an input to it. On your Haskell command prompt, type any character with double or single quotation.

```haskell
Prelude> :t "a"
```

It will produce
```console
"a" :: [Char]
```

Remember you use (**:t**) while supplying the input. In the above, **(:t)** is to include the specific type related to the inputs. We will learn more about this type in the upcoming chapters.

Haskell follows conventional ASCII encoding style.
