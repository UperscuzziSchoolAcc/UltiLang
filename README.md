# UltiLang, The Ultimate Language

### Syntax
All lines of code in Ultilang end with a `>:)`.
```python
doStuff()>:)
```
This is because this is the face every programmer makes when their code works.
#### Variables
Ultilang is dynamically typed language, declaring a variable is as easy as:
```python
foo = True>:)
```
To save on memory usage, Ultilang stores variables on the Disk as opposed to the RAM. To access a variable, you need to open the variables file.
```python
foo = True>:) # writes 'True' to foo.var
openVariable(foo)>:) # opens foo.var and returns the value
```
###### Note: You need to call `openVariable()` to access a variable every time. Due to this, Ultilang is now the most memory efficient programming language ever made.

#### Outputting
We took some inspiration from Java with our print function.
```python
system.console.stdout.out.log.output.print.here.new.newLine("hi")>:)  # prints 'bye'
```
###### Note: None of the methods listed have any methods besides the ones used to get to the `newLine()` function.

##### Stderr
We have a function for throwing errors and halting the programs execution.
```python
uhoh("Error encountered")>:)
```
This function also resets your computer (doesn't work on Arch it's too hard)

#### Lists
In Ultilang, lists are called Ultilang Dynamic Sequential Binary Element Catalog Data Type. For the sake of time, we will call then UDSBECDT.

UDSBECDT are declared using a `(|` to start, and a `}])` to end it, and the indexes are separated by their index number instead of a comma. This separation tactic helps the programmer get the index of a literal without counting, because who has time for that?
```python
Ultilang Dynamic Sequential Binary Element Catalog Data Type = (|"dog"0 "cat"1 "toucan"}])>:)
# Variables can have whitespace in their names
```

#### Numbers
Numbers are stored using ASCII, so a number is 1 byte per digit.
##### What weird languages do:
```
11111111 = 255 -- 1 byte
```
##### What Ultilang does:
```
00110010 00110101 00110101 = 255 -- 3 bytes
```
This means, technically, that numbers are strings. But they aren't numbers because \[PUTREASONHERE]

#### Functions
Functions have different keywords depending on what language you use:
```yaml
Python: 'def'
JavaScript: 'function'
Kotlin: 'fun'
Rust: 'fn'
```
This may be confusing for new programmers that are looking over Ultilang code, this is our solution.

```python
thisisafunction foo&out& [ # we subsitiuted parentheses for 'and' symbols
  system.console.stdout.out.log.output.print.here.new.newLine(openVariable(out))>:)
  # `openVariable()` is called on function arguments 
]
callFunction(openVariable(foo), "Hello, world!")>:) # functions are also stored as files, and you call them using callFunction()
```
##### Note: Arguments are separated just like index's in UDSBECDTs, by their index number.
##### Also note that recursive functions have a keyword: `thisisarecursivefunction`, and it is REQUIRED for recursive functions.

#### Structs
Structures are defined by the `structure` keyword.
```python
structure Vector3 [
  x 1 # variables are separated by their index
  y 2
  z 3
]
```
Structures are stored as json files, in a `structureTemplates` folder. While running this code, your file system should look like this:
```
.
├── structureTemplates
│   └── Vector3.json 
└── main.ulti
```
You can assign a structure to a variable like this:
```python
vector3Value = structure Vector3>:)
```
