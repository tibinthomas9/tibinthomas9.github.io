---
layout: post
title: iOSRefrsher!
image: /img/hello_world.jpeg
---
# iOS and Swift Refresher

***Must Refer***

[swift apple documentation](https://developer.apple.com/documentation/swift)
[swift lang documentation](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)
[swift tutorials point](https://www.tutorialspoint.com/swift/index.htm)
### iOS Basic Info

 - iPhone OS(first name)
 - Unix based
 - first os with muti touch GUI,in their words a phone that runs macOS
 - Latest Version - 12.2
 - Privacy oriented

### Languages

 - **swift**

    Curent version: swift 5.0
    open source
    modern and better performance than objective c
    
  - **objective** c    (header(.h) and implementation (.m) files ) 

    Programming language for NeXTSTEP OS
 - **c and c++** (limited)



 
#  Swift Language
Swift includes modern features like type inference, optionals, and closures, which make the syntax concise yet expressive. Swift ensures your code is fast and efficient, while its memory safety and native error handling make the language safe by design. Writing Swift code is interactive and fun in Swift Playgrounds, playgrounds in Xcode, and REPL.
 - ## Constants and Variables
    Variables are nothing but *reserved memory locations to store values*. This means that when you create a variable, you reserve some space in memory
 

 

	> **let** : constant  
	> **var**: variable

 -    **Type Annotations**
Telling the type of a variable or constant
 

>     var name: String

 - **Type Inference**
 The ability of Swift's compiler to figure out what kind of data type should be assigned to each of your variables and constants, so you don't have to explicitly state it.
 

>     var name = "Swift"

 - **Type Aliases**

	_Type aliases_  define an alternative name for an existing type. You define type aliases with the  `typealias`  keyword.
- **Type Coversion**

	`SomeType(ofInitialValue)` is the default way to call the initializer of a Swift type and pass in an initial value.
	
-	**[Typecasting](https://medium.com/@abhimuralidharan/typecastinginswift-1bafacd39c99)**

	 _Type casting_  is a way to check the type of an instance, or to treat that instance as a different superclass or subclass from somewhere else in its own class hierarchy.

	Type casting in Swift is implemented with the  **`is`  and  `as`**  operators. These two operators provide a simple and expressive way to check the type of a value or cast a value to a different type.
 - **Naming**
 Constant and variable names can’t contain whitespace characters, mathematical symbols, arrows, private-use Unicode scalar values, or line- and box-drawing characters. 

	 Nor can they begin with a number, although numbers may be included elsewhere within the name


  

 - ## Data Types

	Based on the data type of a variable, the operating system allocates memory and decides what can be stored in the reserved memory.

	### Built-in Data Types
	In Swift Data types are ***internally implemented as structs***.

	The swift standard library contains **Int,Double,String,Array,Dictionary** as structs,

	Swift  offers the programmer a rich assortment of built-in as well as user-defined data types. The following types of basic data types are most frequently when declaring variables −

	-   **Int or UInt**  − This is used for whole numbers. More specifically, you can use Int32, Int64 to define 32 or 64 bit signed integer, whereas UInt32 or UInt64 to define 32 or 64 bit unsigned integer variables. For example, 42 and -23.
	    
	-   **Float**  − This is used to represent a 32-bit floating-point number and numbers with smaller decimal points. For example, 3.14159, 0.1, and -273.158.
	    
	-   **Double**  − This is used to represent a 64-bit floating-point number and used when floating-point values must be very large. For example, 3.14159, 0.1, and -273.158.
	    
	-   **Bool**  − This represents a Boolean value which is either true or false.
	    
	-   **String**  − This is an ordered collection of characters. For example, "Hello, World!"
	    
	-   **Character**  − This is a single-character string literal. For example, "C"
	    
	-   **Optional**  − This represents a variable that can hold either a value or no value.
	    
	-   **Tuples**  − This is used to group multiple values in single Compound Value.
	    

	 Few important points related to Integer types −

	-   On a 32-bit platform, Int is the same size as Int32.
	    
	-   On a 64-bit platform, Int is the same size as Int64.
	    
	-   On a 32-bit platform, UInt is the same size as UInt32.
	    
	-   On a 64-bit platform, UInt is the same size as UInt64.
	    
	-   Int8, Int16, Int32, Int64 can be used to represent 8 Bit, 16 Bit, 32 Bit, and 64 Bit forms of signed integer.
	    
	-   UInt8, UInt16, UInt32, and UInt64 can be used to represent 8 Bit, 16 Bit, 32 Bit and 64 Bit forms of unsigned integer.

## Tuples

_Tuples_  group multiple values into a single compound value. The values within a tuple can be of any type and don’t have to be of the same type as each other.

    1.  let http404Error = (404, "Not Found")
    2.  // http404Error is of type (Int, String), and equals (404, "Not Found")

Tuples are useful for temporary groups of related values. They’re not suited to the creation of complex data structures.
    	

	    



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc4NjczMzE2OCw4MjY2MjMwNjksNTA5ND
QyMTY1LDIwNzY5NjI3MzVdfQ==
-->