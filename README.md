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


***ALTERNATES !***

A. IF YOU ARE DECLARING AND DEFINING AT THE SAME TIME, NEED NOT STATE THE DATATYPE
```go
    var [varname] = [data of datatype]
```

B. SHORTHAND PROPERTY

```go
    [varname] := [data of datatype]
```

