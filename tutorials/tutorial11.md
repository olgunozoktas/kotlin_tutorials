# Inheritance

In this tutorial, we are going to learn how to use inheritance in the kotlin programming language

## Inherit Class

~~~~

Ex:

class Sum:Div() {
	fun sum(a: Int, b: Int): Int {
		return a + b
	}
}

//to make a class inheritable we have to write **open** keyword so

open class Div {
	fun div(a: Int, b: Int): Int {
		return a / b
	}
}

//Lets use those

val op = Sum()
println(op.sum(5,3))
println(op.div(20,4)) //we could use div because **Sum** class inherited **Div**

~~~~