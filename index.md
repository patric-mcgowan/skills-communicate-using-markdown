# H1
## H2
### H3
#### H4
H0
##### H5
H0
###### H6
H0

```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

``` javascript
var myVar = "Hello, world!";
```

``` python
def my_function():
    print("Hello, world!")
```

``` bash
$ echo "Hello, world!"
```

``` html
<!DOCTYPE html>
<html>
    <head>
        <title>Hello, world!</title>
    </head>
    <body>
        <h1>Hello, world!</h1>
    </body>
    </html>
  ```

  ``` css
  h1 {
      color: blue;
  }
  ```

  ``` sql
  SELECT * FROM table;
  ```

  ```  ruby
  puts "Hello, world!"
  ```

  ``` c
  #include <stdio.h>
  ```

  ``` c++
  #include <iostream>
  ```

  ``` c#
  using System;
  ```

  ``` java
  public class HelloWorld {
      public static void main(String[] args) {
          System.out.println("Hello, world!");
      }
  }
  ```

  ``` json
  {
      "key": "value"
  }
  ```

  ``` yaml
  key: value
  ```

  ``` toml
  key = "value"
  ```

  ``` ini
    
    ```

  ``` diff
  - Hello, world!
  + Goodbye, world!
  ```

  ``` plaintext
  Hello, world!
  ```

  ``` markdown
  # Hello, world!
  ```

  ``` xml
  <tag>Hello, world!</tag>
  ```

  ``` php
  <?php
  echo "Hello, world!";
  ?>
  ```

  ``` perl
  print "Hello, world!";
  ```

  ``` scala
  println("Hello, world!")
  ```

  ``` swift
  print("Hello, world!")
  ```

  ``` go
  package main

import "fmt"

type test struct {
	value string
}

func (t *test) printPtr(prefix string) {
	fmt.Println(prefix, t.value)
}

func (t test) getAsValue(prefix string) {
	fmt.Println(prefix, t.value)
}

func main() {
	t := test{value: "initial value"}
	ptrFn := t.printPtr
	valueFn := t.getAsValue // This results in the original struct being copied

	ptrFn("Initial ptr value: ") // This will print "initial value"
	valueFn("Initial value: ")   // This will print "initial value"

	t.value = "new value"
	ptrFn("New ptr value: ") // This will print "new value"
	valueFn("New value: ")   // This will print "initial value"
}
```

``` rust
fn main() {
    println!("Hello, world!");
}
```

``` kotlin

    fun main() {
    println("Hello, world!")
}
```

``` groovy
println "Hello, world!"
```

``` vb

    Module Module1
    Sub Main()
        Console.WriteLine("Hello, world!")
    End Sub
End Module
```

``` lua
print("Hello, world!")
```

``` matlab
disp('Hello, world!')
```

``` r
print("Hello, world!")
```

``` julia
println("Hello, world!")
```

``` powershell
Write-Host "Hello, world!"
```

``` shell
echo "Hello, world!"
```

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)