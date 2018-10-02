# Kotlin Switch

In this tutorial, we are going to learn kotlin style switch case in the kotlin programming language.

## Define Kotlin Switch

~~~~

Ex: 

val day = 3
var dayString = ""

when(day) {
	1 -> dayString = "Monday"
	2 -> dayString = "Tuesday"
	3 -> dayString = "Wednesday"
	else -> dayString = "Do not know it"
}

println(dayString)

~~~~

Result: "Wednesday"

~~~~

Ex: 

    val day = 4
    var dayString = when(day) {
        1 -> "Monday"
        2 -> "Tuesday"
        3 -> "Wednesday"
        else -> "Do not know it"
    }

    println(dayString)

~~~~

In this example, it will return a value like "Monday","Tuesday","Wednesday" or "Do not know it"

Result: "Do not know it"