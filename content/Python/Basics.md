---
title: Basics
---
## Variables 
Variables are labels that we can assign to values or boxes in which we can store data.
For example,
`name = Siddhant`
Here name is a variable that has the value siddhant. 

### Naming and Using variables
Variable names can contain only letters, numbers, and underscores. They can start with a letter or an underscore, but not with a number. For instance, you can call a variable `message_1` but not `1_message`.

### Data Types
#### String 
A string is a series of characters. In python, anything within quotes (single or double) is considered a string.
`This is a string`

##### Changing case in a string with methods
```name = - "siddhant adhikari"
   name = name.title()
   print(name)
   #output = Siddhant Adhikari
   name = name.lower()
   print(name)
   #output = siddhant adhikari
   name = name.upper()
   print(name)
   #output = SIDDHANT ADHIKARI
```
Here upper, lower and title are known as methods that perform a certain action on the strings. The dot after name tells python to perform the title action on the name and the parenthesis () are used for providing any other additional information for methods as methods often require additional info. The above methods are quite simple so they do not require any additional info.

##### Using variables in strings
```first_name = "siddhant"
   last_name = "adhikari"
   full_name = f"{first_name} {last_name}"
   print(f"Have a nice day,  {full_name}")
```

When using variable names to output the value stored use curly braces {} and f before the quotation. [f-strings](https://www.geeksforgeeks.org/python/formatted-string-literals-f-strings-python/) refers to format strings

##### Adding whitespaces
Whitespaces simply refer to end of lines, tabs, or spaces.
`print(Games\n\tcricket\n\tchess\n\golf)`
This adds a new line and a tab spacing.]

##### Stripping whitespace
 Use strip() method. lstrip and rstrip for removing whitespace from left or right respectively.
##### Removing prefixes
Use removeprefix() method. 
```url = "https://youtube.com"
   new_url = url.removeprefix(https://)
   print(new_url)
```



