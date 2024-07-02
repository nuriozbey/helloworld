# Hello World in All Programming Languages
This repository contains the code for printing "Hello, World!" in all programming languages.

[![AUR last modified](https://img.shields.io/badge/last%20modified-02.07.2024-orange)]()
[![GitHub last commit](https://img.shields.io/github/last-commit/nuriozbey/helloworld)]()
[![GitHub repo size](https://img.shields.io/github/repo-size/nuriozbey/helloworld)]()
[![GitHub](https://img.shields.io/github/license/nuriozbey/helloworld)]()


## Languages

<br>
<table>
<tbody>
 <tr>
 <td align="center" width="16%">
<span><b><center>C++</center></b></span> 
<br>
<img height=65px src="https://cdn.svgporn.com/logos/c-plusplus.svg">
</td>

<td align="center" width="16%">
<span><b><center>C</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/c.svg">
</td>

<td align="center" width="16%">
<span><b><center>Go</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/go.svg">
</td>

<td align="center" width="16%">
<span><b><center>HTML</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/html-5.svg">
</td>

<td align="center" width="16%">
<span><b><center>Java</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/java.svg">
</td>

<td align="center" width="16%">
<span><b><center>JavaScript</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/javascript.svg">
</td>
</tr>

<tr>
<td align="center" width="16%">
<span><b><center>PHP</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/php.svg">
</td>

<td align="center" width="16%">
<span><b><center>Perl</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/perl.svg">
</td>

<td align="center" width="16%">
<span><b><center>Ruby</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/ruby.svg">
</td>

<td align="center" width="16%">
<span><b><center>Shell</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/bash.svg">
</td>

<td align="center" width="16%">
<span><b><center>Swift</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/swift.svg">
</td>

<td align="center" width="16%">
<span><b><center>Kotlin</center></b></span>
<br>
<img height=65px src="https://cdn.svgporn.com/logos/kotlin.svg">
</td>
</tr>

</tbody>
</table>


## Table of Contents
- [C](#c)
- [CPP](#cpp)
- [Go](#go)
- [HTML](#html)
- [Java](#java)
- [JavaScript](#javascript)
- [PHP](#php)
- [Perl](#perl)
- [Ruby](#ruby)
- [Shell](#shell)
- [Swift](#swift)
- [Kotlin](#kotlin)

## Contributing
If you want to add a new programming language, please follow the steps below:
1. Create a new folder with the name of the programming language.
2. Add the code for printing "Hello, World!" in the new programming language.
3. Add the build and run instructions in the README.md file.
4. Create a pull request.


## CPP

### Code
```cpp
#include <iostream>
int main() {
    std::cout << "Hello, World!";
    return 0;
}
```
### Build
```bash
g++ hello.cpp -o hello_cpp
```

### Run
```bash
./hello_cpp
```

## C

### Code
```c
#include <stdio.h>
int main() {
    printf("Hello, World!");
    return 0;
}
```

### Build
```bash
gcc hello.c -o hello_c
```

### Run
```bash
./hello_c
```

## Go

### Code
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

### Build
```bash
go build -o hello_go hello.go
```

### Run
```bash
./hello_go
```

## HTML

### Code
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

## Java

### Code
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### Build
```bash
javac HelloWorld.java
```

### Run
```bash
java HelloWorld
```

## JavaScript

### Code
```javascript
console.log("Hello, World!");
```
### Run
```bash
node hello.js
```

## PHP

### Code
```php
<?php
echo "Hello, World!";
?>
```

### Run
```bash
php hello.php
```

## Perl

### Code
```perl
#!/usr/bin/perl
use strict;
use warnings;

print "Hello, World!\n";
```

### Run
```bash
perl hello.pl
```

## Ruby

### Code
```ruby
puts "Hello, World!"
```

### Run
```bash
ruby hello.rb
```


## Shell

### Code
```bash
#!/bin/bash
echo "Hello, World!"
```

### Run
```bash
bash hello.sh
```

## Swift

### Code
```swift
print("Hello, World!")
```

### Build
```bash
swiftc hello.swift -o hello_swift
```

### Run
```bash
./hello_swift
```

## Kotlin

### Code
```kotlin
fun main() {
    println("Hello, World!")
}
```

### Build
```bash
kotlinc hello.kt -include-runtime -d hello_kotlin.jar
```

### Run
```bash
java -jar hello_kotlin.jar
```
