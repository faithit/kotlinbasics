📖 Kotlin Basics — Step by Step Guide

1️⃣ Variables and Data Types

✅ Variables

val — Immutable (cannot change)

var — Mutable (can change)

val language = "Kotlin"
var age = 18
age = 19

✅ Data Types

Data Type

Example

Description

Int

val age = 25

Integer numbers

Double

val price = 19.99

Decimal numbers

Boolean

val isActive = true

True or False

String

val name = "Faith"

Text

Char

val grade = 'A'

Single character

2️⃣ Operators

✅ Arithmetic Operators

Operator

Description

Example

+

Addition

a + b

-

Subtraction

a - b

*

Multiplication

a * b

/

Division

a / b

%

Modulus

a % b

✅ Comparison Operators

Operator

Description

==

Equal to

!=

Not equal to

>

Greater than

<

Less than

>=

Greater or equal to

<=

Less or equal to

✅ Logical Operators

Operator

Description

&&

Logical AND

`



`

Logical OR

!

Logical NOT

3️⃣ Conditional Statements

✅ if / else

val age = 18
if (age >= 18) {
    println("You are an adult")
} else {
    println("You are underage")
}

✅ when Expression

val day = 3
when(day) {
    1 -> println("Monday")
    2 -> println("Tuesday")
    3 -> println("Wednesday")
    else -> println("Other Day")
}

4️⃣ Loops

✅ for Loop

for (i in 1..5) {
    println(i)
}

✅ while Loop

var count = 5
while (count > 0) {
    println("Countdown: $count")
    count--
}

5️⃣ Functions

✅ Declaring and Calling Functions

fun greet(name: String): String {
    return "Hello, $name"
}

println(greet("Faith"))

✅ Single-expression Function

fun square(number: Int) = number * number

println(square(5))  // 25

6️⃣ Null Safety

var name: String? = null
println(name?.length)  // Safe call, prints null instead of crashing

7️⃣ Collections

✅ List Example

val fruits = listOf("Apple", "Banana", "Orange")
for (fruit in fruits) {
    println(fruit)
}

✅ Mutable List Example

val numbers = mutableListOf(1, 2, 3)
numbers.add(4)
println(numbers)

8️⃣ Classes and Objects

class Student(val name: String, var age: Int) {
    fun display() {
        println("$name is $age years old.")
    }
}

val student = Student("Faith", 20)
student.display()

9️⃣ Data Classes

data class User(val id: Int, val name: String)

val user = User(1, "Faith")
println(user)

🔟 Practice Exercises

Declare variables with val and var

Use if / else to check a condition

Write a simple loop to print numbers

Write a function that adds two numbers

Declare a nullable variable and print its safe call

Create a list and loop through it

Create a simple class with a method

🔗 Back to Introduction
