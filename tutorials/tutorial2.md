# Arrays

In this tutorial, we are going to learn how to use arrays in the kotlin programming language.

## Defining Arrays

~~~~

Ex: There are many way to define an array in kotlin

1. Way with the size - Can use another ways as well

val myArray = arrayOfNulls<String>(4) // 4 is the size of the array

myArray[0] = "James"
myArray[1] = "Lars"
myArray[2] = "Kirk"
myArray[3] = "Rob"
print(myArray[0])

Result: James

2. Way with the pre-defined elements

val myNumberArray = intArrayOf(10,20,30,40,50)
println(myNumberArray.size) 

Result: 5

3. To change the wanted index value

myNumberArray.set(2,35) //30 will be 35
println(myNumberArray[2])

4. To get an element from the array

We could use traditional way like **println(myNumberArray[2])** or we can write **println(myNumberArray.get(2))**

~~~~
