# Sets

In this tutorial, we are going to learn how to use sets in the kotlin programming language.

## Define Sets

In the sets, every element has to be unique

~~~~

Ex:

val mySet = HashSet<String>()

mySet.add("Kirk")
mySet.add("Kirk")

println(mySet.size)

Result: 1 //because it does not add the second "Kirk"

~~~~