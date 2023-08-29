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
This function also resets your computer (doesn't work on Arch its too hard)

#### Lists
In Ultilang, lists are called Ultilang Dynamic Sequential Binary Element Catalog Data Type. For the sake of time, we will call then UDSBECDT.

UDSBECDT are declared using a `(|` to start, and a `}])` to end it, and the indexes are separated by their index number instead of a comma. This separation tactic helps the programmer get the index of a literal without counting, because who has time for that?
```python
Ultilang Dynamic Sequential Binary Element Catalog Data Type = (|"dog"0 "cat"1 "toucan"}])
# Variables can have whitespace in their names
```

#### Numbers
Numbers are stored using ASCII, so a number is 1 byte per digit.
##### What weird languages do:
```
11111111 = 256 -- 1 byte
```
##### What Ultilang does:
```
00110010 00110101 00110110 = 256 -- 3 bytes
```
