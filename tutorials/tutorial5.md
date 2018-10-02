# Maps

In this tutorial, we are going to learn how to use **Maps** in the kotlin programming language

## Define Maps

In the maps instead of adding just the values, also we have to add a key as well to be sure that to get the value by looking its key

~~~~

Ex: 

val myHashMap = HashMap<String, String>()
myHashMap.put("name","James")
myHashMap.put("instrument","Guitar")

println(myHashMap["instrument"]) //according to the key it will print the value

~~~~