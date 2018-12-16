# python object oriented programing 

What is a class ?

 A class is a blue print that provides structure for how an object should be defines but doesn’t provide any real content itself.



 *** Remember that it is best practice for a class name to begin with a capital letter *** ```Animal``` not ```animal```

 *** This is example on how to define a class in python ***

 ``` class Animal:```

 # What is an object 

 an object is an instance of a class 

you can think of a class as a blue print for a house and an object as the actual house


### here is an example on  how to create a new object in python

``` new_animal = Animal()```

once you create a new class you need to Initialize the properties. you can think of properties as a variable for your object since properties can store data 

before you can use a property you must Initialize it 

Initialize your properties will allow you to pass values to you object later on when you create a new object. 

### here is an example on  how to Initialize your an object instance &properties 

``` def __init__(self, name, age): self.name = name self.age = age```

setting a default value will allow you to not have to pass a number value to one of you properties

 here is an example on  how to  set a default value
for your properties

```def __init__(self, name, age=19): self.name = name self.age = age```

### passing data to a new created object 

```new_animal = Animal("jack", 10)```




 ## What are methods? 

 A method defines the behavior of a class 

 you could also think of as a function for objects

 ## Polymorphism: 

A method that can have many uses 




 ### Here is an example of a method

 ``` def print_name(self): return "hello my name is {}".format(self.name)```

you can call the method by appending it to the instance of your object

### an example on how to do that is 

``` who_am_i = Me(): who_am_i.print_name()```
this will call the print_name method and print the name

### What is self?

self represents the instance of the class. By using the "self" keyword we can access the attributes and methods of the class in python.

```__init__``` is a reseved method in python classes. It is known as a constructor in object oriented concepts. This method called when an object is created from the class and it allow the class to initialize the attributes of a class.


## what is inheritance

inheritance allows you to inherits a parents class properties and methods

### here is an example of inheritance

```Dog(Animal):```

Now Dog the child class can inherit the methods and properties of Animal the parent class


## What is method overiding 

method overiding is when a child class inherits a parent class  methods  & properties and want's to make changes to those methods  & properties.

### Here is an example 

```class Parent(object): def __init__(self):self.value = 5 def get_value(self): return self.value class Child(Parent): def get_value(self): return self.value + 1```


### What is Polymorphism

When a child class inherits a method from a parent class and 
you change the behavior of that method that is polymorphism 

















