# Swift Fundamentals

Welcome to the Swift Fundamentals repository! This repository is designed to provide a comprehensive introduction to the basic concepts of Swift programming. Whether you're a beginner looking to learn the fundamentals or an experienced developer brushing up on your skills, you'll find valuable information and examples here.

## Table of Contents

1. [Variables](#variables)
2. [Types of Variables](#types-of-variables)
3. [Optionals & Unwrap](#optionals--unwrap)
4. [Loops](#loops)
5. [Functions](#functions)
6. [Classes & Structs](#classes--structs)

## Variables

In Swift, variables are used to store and manage data. Learn about the various data types and how to declare and use variables effectively.

```swift
// Example of declaring a variable
var myVariable: Int = 42
```

## Types of Variables

Swift provides a rich set of data types. Explore the different types of variables, including integers, floating-point numbers, strings, and more.

```swift
// Example of different variable types
var age: Int = 25
var temperature: Double = 98.6
var name: String = "John Doe"
```

## Optionals & Unwrap

Understanding optionals is crucial in Swift. Learn how to handle situations where a variable may or may not have a value, and master the art of safely unwrapping optionals.

```swift
// Example of using optionals and unwrap
var optionalValue: Int? = 10
if let unwrappedValue = optionalValue {
    print("The value is \(unwrappedValue)")
} else {
    print("The optional is nil")
}
```

## Loops

Loops are essential for repetitive tasks. Explore different types of loops in Swift, such as `for-in` and `while`, and see how they can be used in various scenarios.

```swift
// Example of a for-in loop
for i in 1...5 {
    print("Iteration \(i)")
}
```

## Functions

Functions allow you to organize your code into reusable blocks. Learn how to define and call functions, pass parameters, and return values.

```swift
// Example of a simple function
func greet(name: String) -> String {
    return "Hello, \(name)!"
}
print(greet(name: "Swift Developer"))
```

## Classes & Structs

Swift supports both classes and structs for creating custom data types. Explore object-oriented programming concepts and learn how to define and use classes and structs.

```swift
// Example of a class and struct
class Person {
    var name: String
    var age: Int

    init(name: String, age: Int) {
        self.name = name
        self.age = age
    }
}

struct Point {
    var x: Double
    var y: Double
}
```

Feel free to explore each section, run the provided examples in a Swift playground, and build upon them to deepen your understanding of Swift fundamentals. Happy coding! 🚀