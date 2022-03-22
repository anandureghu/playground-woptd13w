# **Welcome!**

> “Go will be the server language of the future.” — Tobias Lütke, Shopify

Welcome to the new Go (Golang) Mastery. 

In past couple of years, there is a rise of new programming language: Go or Golang. Go is a statically typed, compiled programming language designed at Google by Robert Griesemer, Rob Pike, and Ken Thompson. Go is syntactically similar to C, but with memory safety, garbage collection, structural typing, and CSP-style concurrency. 

> “Modern processors are a like nitro fueled funny cars, they excel at the quarter mile. Unfortunately modern programming languages are like Monte Carlo, they are full of twists and turns.” — David Ungar

* Goroutines have growable segmented stacks. That means they will use more memory only when needed.

* Goroutines have a faster startup time than threads.
Goroutines come with built-in primitives to communicate safely between themselves (channels).

* Goroutines allow you to avoid having to resort to mutex locking when sharing data structures.

* Also, goroutines and OS threads do not have 1:1 mapping. A single goroutine can run on multiple threads. Goroutines are multiplexed into small number of OS threads.

All the above points, make Go very powerful to handle concurrency like Java, C and C++ while keeping concurrency execution code strait and beautiful like Erlang.

![Go](https://miro.medium.com/max/700/1*nlpYI256BR71xMBWd1nlfg.png)


# Code written in Go is easy to maintain.
Let me tell you one thing. Go does not have crazy programming syntax like other languages have. It has very neat and clean syntax.

The designers of the Go at google had this thing in mind when they were creating the language. As google has the very large code-base and thousands of developers were working on that same code-base, code should be simple to understand for other developers and one segment of code should has minimum side effect on another segment of the code. That will make code easily maintainable and easy to modify.
Go intentionally leaves out many features of modern OOP languages.

* No classes. Every thing is divided into packages only. Go has only structs instead of classes.
* Does not support inheritance. That will make code easy to modify. In other languages like Java/Python, if the class ABC inherits class XYZ and you make some changes in class XYZ, then that may produce some side effects in other classes that inherit XYZ. By removing inheritance, Go makes it easy to understand the code also (as there is no super class to look at while looking at a piece of code).
* No constructors.
* No annotations.
* No generics.
* No exceptions.

Above changes make Go very different from other languages and it makes programming in Go different from others

# Go is backed by Google.
* I know this is not a direct technical advantage. But, Go is designed and supported by Google. Google has one of the largest cloud infrastructures in the world and it is scaled massively. Go is designed by Google to solve their problems of supporting scalability and effectiveness. Those are the same issues you will face while creating your own servers.
* More to that Go is also used by some big companies like Adobe, BBC, IBM, Intel and more.([Source](https://github.com/golang/go/wiki/GoUsers))

> Even though Go is very different from other object-oriented languages, it is still the same beast. Go provides you high performance like C/C++, super efficient concurrency handling like Java and fun to code like Python/Perl.

> If you don’t have any plans to learn Go, I will still say hardware limit puts pressure to us, software developers to write super efficient code. Developer needs to understand the hardware and make their program optimize accordingly. The optimized software can run on cheaper and slower hardware (like IOT devices) and overall better impact on end user experience.