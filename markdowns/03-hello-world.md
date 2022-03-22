# **Hello World!**

>A "Hello, World!" program is generally a computer program that outputs or displays the message "Hello, World!". This program is very simple to write in many programming languages, and is often used to illustrate a language's basic syntax.

So lets start with writing a Hello world  Program,

@[Hello World]({"stubs": ["03-hello-world.go"], "command": "go test 03-hello-world_test.go"})

We will practise most of our programs in official [**Go Playground**](https://go.dev/play/).

Try running this code on the playground and see what happens.

# Code review
>package main

This is to represent the root program on our entire project.

The first file runnning will be the main package code.

> func main(){
> 
> 
> }

The code inside the {} is called the function body. We will talk more details of function in the functions lecture.

when the code runs the first excuting code will be the main function body.

> fmt.Println("Hello World")

fmt is a built in package in Go that will help us taking input and output from and to user.

fmt is a most important package that we are going to use more in the upcoming lectures.