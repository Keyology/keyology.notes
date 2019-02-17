# Golang notes

## Packages Golang

Every go package/application starts with the main package

`package main`

Go handles `public` and `private` using casing, if a function is public the function will be capital if it’s
Private it will be lower case

`public` - means you can access the function in other files.

`private` means you can not access the file in another method.

To import go packages use the import statement

`import ""fmt""`

to import multiple packages

```import (
    ""fmt""
    ""math""
)

```

You can access any function variable struct etc without calling the package name if it belongs to that package otherwise you have to call the package name before calling the function, variable, struct.

Go enforces that you use all the packages you import otherwise it will throw an error.

Go package names must always be lower case and be a single word.

this
`package hello`

not this

`package helloworld or package Hello world`

Every go file must have a package name

To import go packages you must use the path starting at github.com

example

`import github.com/go-redis/redis`

Go fmt will reorganize your code to make it neat.
Just run go fmt < name of file >

## variables

Data types

bool

string

int int8 int16 int32 int64

uint uint8 uint16 uint32 uint64 uintptr

byte - alias for uint8

rune - alias for int32

represents a Unicode code point

float32 float64

complex64 complex128


Inside a function you can use short assignment := for varibles

Constants cannot be declared using the := syntax.


Uint can only hold whole positive numbers

Go requires that you don’t have unused variables otherwise it will throw an error 

Variable name must start with a letter 

_ is a unknown value you can use as a variable place holder






