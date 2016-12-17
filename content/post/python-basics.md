+++
description = ""
categories = [
  "",
]
tags = [
  "",
  "",
]
date = "2016-12-04T12:27:32+05:30"
title = "Python Basics"

+++

# Introduction

Python is a general purpose scripting language that can be used to build simple programs to rocket science. Since it is quite simple to use and also powerful, it has wide variety of applications. 

## Creating Variables In Python

Like JavaScript, Python variables are untyped and can store numbers, strings and floats. However, each variable is an object, and this has its own method and properties. 

{{< codecaption lang="python" title="Variables In Python" >}}
name = "Saurav"
age = 23
height = 162.3
del name # delete the name variable
{{< /codecaption >}}

However, unlike other languages, Python data types do not have a limit, and can be big or small precision as the memory of your computer. 

## Operation With Variables In Python

{{< codecaption lang="python" title="Variable Operations" >}}
0.1 + 0.1 + 0.1 - 0.3 # will give a vary small precision value
3/3 # will give a float, as division always yields floats
int(3.8) # parsing an int, will chop off the float value and give only 3
{{< /codecaption >}}

You can use any mathametical functions like other languages. However, floats are a bit tricky, so need special attention.

## Strings In Python

Like most other languages, Strings in python are enclosed in quotes. There are different ways of declaring it though. 

{{< codecaption lang="python" title="Creating Strings In Python" >}}
name = 'Saurav` # single quotes
place = "Chinsurah" # double quotes
address = ''' Rowville Avenue,
	55 Sahaganz
	New Dehli. ''' # triple quotes, can also contain new lines
age = str(25) # calling the string constructor
sentence = 'Roy"s bike' # different quotes
sen2 = 'Roy\'s second bike' # escape characters
{{< /codecaption >}}

Like other languages, you can concatenate strings too, using the plus sign. However, remember, to convert numbers to string before concatenating. 

{{< codecaption lang="python" title="Operations On Strings" >}}
full_name = 'Saurav' + "Modak"
address = str(5) + 'rowland street'
five_equals = '=' * 5 # will display equals sign 5 times
{{< /codecaption >}}

Strings can also be used as templates, and can help in formatting things. 

{{< codecaption lang="python" title="Formatting Strings" >}}
status = 'Hello, {}. My name is {}.'
print(status.format('World', 'Saurav'))
{{< /codecaption >}}

## Lists In Python

Like other languages, Python allows you to store number of items inside an array, which is called lists in python. 

{{< codecaption lang="python" title="Lists in Python" >}}
my_list = [1, 2, 3]
my_list.append(4) # appends an item
my_list.extend([6, 7]) # appends multiple items
my_list += [8, 9] # concat works
my_list * 2 # list times twice
my_list.remove(3) # will remove no. 3 from list
{{< /codecaption >}}

Ofcourse, you can use string and lists together, with several cool functions python offers. 

{{< codecaption lang="python" title="Lists in Python" >}}
"Saurav is my name".split() # will split the string into arrays by the whitespace
" ".join(["Saurav", "is", "my", "name"]) # will join it back together
{{< /codecaption >}}

## Calling Functions

Functions let you group several statements and do tasks. Like other languages, they can be called easity. 

{{< codecaption lang="python" title="Calling Functions" >}}
print("Hello, World")
{{< /codecaption >}}

## The Python Shell And Running Python Programs

Like most scripting languages, python provides a shell where you can test programs and functions temporarily. It has a read-eval-print loop, so you get the output instantly. 

More powerful shell implementation exists, including ipython and jupyter notebook. 

To run a python program, you call

`python filename.py`
