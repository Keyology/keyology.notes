 #enums in swift
 
 you create an enums for data that is not going to change or  for perdictiable data that is not going to change.

 Use enums when you have a limited number of data that is not going to change

 How to create a enum 

```
enum Directions {
case up
case down 
case left 
case right

}
```

Assigning  enum to a variable

``` var dir = Direction.North ```

``` print(dir.rawValue) ```


passing raw values

raw value is a value thay is assign to an enum that can't be changed an example is if you create a case and you want it to have a specific value you can use a raw vale*/

 specify a type  to a enum only when you asssign a raw value 

```
enum Direction : String{
    case North = "You are heading north"
    case South = "You are heading south"
    case East = "You are heading east"
    case West = "You are heading west"
    
    
}
```







