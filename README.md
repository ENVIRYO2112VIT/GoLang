# GoLang

### Reference Docs:
1. [Programiz.com][1]
2. [GoLang Official Documentation][2]

[1]: https://www.programiz.com/golang/
[2]: https://go.dev/

## Introduction:

Made by 3 developers at google, the main aim was to overcome the deficiency showed by C++ and Python in their development capabilities.

The language is specially popular because it consists of THE BEST OF ALL WORLDS(programming languages): eg. Garbage collection of Java

***NOTE: SEMI-COLONS FREE !!(PHEW)***


## Starter Template:

```go
package main

import "fmt"  //Used for printing and normal FORMATTING
//FMT IS STILL NOT THE "BARE MINIMUM"

func main()  {
	fmt.Print("Hello World")
}
```
## Let's Dive In !

### Variables in GoLang:

**Declaration:**
```go
var [varname] [datatype]
```
No Values assigned? Dont worry, it will take the default value for the mentioned datatype.

**Definition:**
```go
var [varname] [datatype] = [value of datatype]
```

**Multiple Variables**
```go
var [varname1], [varname2], ...., [varnameN] [datatype]
```

***ALTERNATES !***

A. IF YOU ARE DECLARING AND DEFINING AT THE SAME TIME, NEED NOT STATE THE DATATYPE
```go
var [varname] = [data of datatype]
```

B. SHORTHAND PROPERTY

```go
[varname] := [data of datatype]
```
### DataTypes in GoLang
**DEFINITION:**
*Do you literally need a definition for this?*

|Datatype CodeName|DataType |GoLang Types |
|--------|--------|-------|
|`int` | Integer| `int` / `uint`(General-32 bits), `int8` / `uint8`, `int16` / `uint16`, `int32` / `uint32`, `int64` / `uint64` |
|`float` | Float(decimal)|`float32`, `float64` |
|`string` | Strings|`string` |
|`bool`| Boolean|`bool`|
|`complex`|Complex Numbers|`complex`|
|`byte`| 8-bit non-negative integers|`byte`|

### Input Output

So basically, as mentioned earlier, `import "fmt"` is not included in the 'bare - minimum template for Go.
However, `fmt` library plays an essential role for fetching input and displaying output, including CUSTOM USER-DEFINED DISPLAY OF OUTPUTS.

### Displaying to user(OUTPUT)

**Print Statement**
There are three kinds of functions to print output messages

1. `fmt.Print()`
2. `fmt.Println()`
3. `fmt.Printf()`

**`fmt.Print()`** 
The most generic and the most common statement for printing any output

***General syntax***
```go
fmt.Print(var1, var2, var3,.......)
```

**`fmt.Println()`** 
This print statement is used to print the output in a new line.
So basically the output is like:

`(YOUR OUTPUT PROVIDED HERE)\n <-- A new line at the end by default`

***General syntax***
```go
fmt.Println(var1, var2, var3,.......)
```

*NOTE: When you wrap any character or variable inside the print fn to be output, then it will be treated as string, not as variable(kinda obvious!)*

**`fmt.Printf()`**
Formally, this function formats the strings and sends them to the screen.

Yes, this is the same one that was used in C! Just some here and there with the placment arguments:

|**Data Type**|Format Specifier|
|----------|----------|
|integer|`%d`|
|float|`%g`|
|string|`%s`|
|bool|`%t`|

**If you are thinking is it possible to do without fmt, yes it is**
1. `println()`
2. `print()`

But it is recommended to use the fmt package for printing, these println and print are used only for debugging purposes.

### Input

The `scan()` function is used to take input in Go

*Syntax:*
```go
var age int
fmt.Print("Enter your age: ")
fmt.Scan(&age)
```

```go
fmt.Scan(&var1, &var2, &var3, ....., &varn);
```




**Variations of Scan:**

1. `fmt.Scan()`
2. `fmt.Scanln()`
3. `fmt.Scanf()`



<!-- FOOTER -->
<div align = "center">
	
---
Made by [Sritam Mishra](https://github.com/ENVIRYO2112VIT "View My Profile")

</div>
