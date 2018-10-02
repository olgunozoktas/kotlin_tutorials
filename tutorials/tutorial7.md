# For Loop

In this tutorial, we are going to learn how to use for loop in the kotlin programming language.

## Define For Loop

~~~~

Ex: Get the numbers one by one from the array

var myNumbers = intArrayOf(12,15,18,21,24)

for(number in myNumbers) {
	print(number) // 12, 15, 18, 21, 24
	val z = number / 3 * 5
	println(z)
}

Ex 2: Get the index of the elements one by one

for(i in myNumbers.indices) { //indices is plural of the index
	print(i) // 0,1,2,3,4
	val y = myNumbers[i] / 3  * 5
	println(y)
}

Ex 3: A will start from 0 to go 9

for(a in 0..9) {
	print(a) // will be 0,1,2,3,4,5,6,7,8,9
	val b = a * 10
	println(b)
}

