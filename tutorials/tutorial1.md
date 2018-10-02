# Kotlin Variables

In this tutorial, we are going to learn the variable usages in the kotlin

## Normal Variables

We can define the variables with the **var** keyword.

~~~~

Ex: 

var x = 5
println(x) 

~~~~

Result: 5

## Constant Variables

To define a constant variable we have to use **val** keyword.

~~~~

Ex: 

val y = 5
println(y)

~~~~

Result: 5

If tried to assign it again as follows:

~~~~

y = 6

~~~~

Result: Error, Val cannot be reassigned.

Because val is immutable, that means cannot be changed, it is constant

## Integer & Doubles

There is not specific type to define for integer & double for kotlin, instead we will use **var** and **val** keys again. Because of its statically typed language, it will choose the type itself.

~~~~

var x = 5 //Integer
var y = 5.0 //Double

~~~~

**y** is actualy is an **float** but as you know **double & float** are the same thing except double holds more digits than float.

## Predefine Variable Types

Sometimes we need to assign a speficic variable type to the variable so we can use the following method.

~~~~

Ex: I want to get an integer so

var r : Int = 5

Ex: I want to get an double so

var y : Double = 4.0

Ex: I want to get an string so

var x : String = "Hey"

Ex: I want to get an boolean so

var z : Boolean = true

~~~~

If the assigned value is not matched with the defined type, then it will throw an error
