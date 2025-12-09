
## Python Data Structures and Boolean

* Boolean
* Boolean and Logical Operators

### Boolean Variables
Boolean values are the two constant objects False and True.

They are used to represent truth values (other values can also be considered false or true).

In numeric contexts (for example, when used as the argument to an arithmetic operator), they behave like the integers 0 and 1, respectively.

The built-in function bool() can be used to cast any value to a Boolean, if the value can be interpreted as a truth value

They are written as False and True, respectively.

```bash
  False
```
   false

```bash
  print(True,False)
  ``` 
True False

```bash
  type(True)
  ``` 
bool

```bash
  type(False)
  ``` 
bool

## Boolean and Logical Operators

```bash
  True and True
  ``` 
True

```bash
  True and False
  ``` 
False

```bash
  True or False
  ``` 

True

```bash
  True or True
  ``` 

True

```bash
  my_str='Krish123'
  my_str.istitle()
  ``` 

True

```bash
print(my_str.isalnum()) #check if all char are numbers
print(my_str.isalpha()) #check if all char in the string are alphabetic
print(my_str.isdigit()) #test if string contains digits
print(my_str.istitle()) #test if string contains title words
print(my_str.isupper()) #test if string contains upper case
print(my_str.islower()) #test if string contains lower case
print(my_str.isspace()) #test if string contains spaces
print(my_str.endswith('k')) #test if string endswith a d
print(my_str.startswith('K')) #test if string startswith H
  ``` 

True

False

False

True

False

False

False

False

True


