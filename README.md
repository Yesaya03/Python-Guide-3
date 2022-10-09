# Python-Guide-3

## Function ( Definition, Calling, Return) ##

### Definition ###
In mathematics, a function is a process that relates an input (input) and an output (output). In Python, besides these relational functions, functions are also a way to organize code - with the ultimate goal of code reusability.

### Create Function ### 
In Python a function is defined using the `def` keyword:

<img width="350" alt="image1" src="https://user-images.githubusercontent.com/61875831/194754467-a87056d8-fb19-4cb0-9616-aeb1fec2e091.png">

### Calling Function ### 
To call a function, use the function name followed by parenthesis:

<img width="350" alt="image1" src="https://user-images.githubusercontent.com/61875831/194754751-f3e355ed-ff81-44b2-8abd-5418fe46441f.png">

### Return Function ### 

* The return [expression] statement will make program execution exit the current function while returning a specified value.
* The return value of a function can be stored in a variable.

For Example:

<img width="696" alt="image1" src="https://user-images.githubusercontent.com/61875831/194758359-0b2c27d4-1da9-4407-b3e7-31c6d0894857.png">

### Pass by Reference vs Value ### 

* All parameters (arguments) in python are "passed by reference". It means that when we change a variable, the data that refers to it will also change, both inside the function and outside the calling function.
* Except, if using assignment operations that will change the reference parameter.

For Example:

<img width="458" alt="image1" src="https://user-images.githubusercontent.com/61875831/194758604-e8376773-de4c-4bff-afd8-431f5e92d3c1.png">

### Arguments & Parameters ### 

Parameters are defined by the names that appear in a function definition, whereas arguments are the values actually passed to a function when calling it. Parameters define what types of arguments a function can accept. For example, given the function definition:

For Example:

<img width="318" alt="image1" src="https://user-images.githubusercontent.com/61875831/194760262-56de76ba-4776-48aa-88e1-c0d6b529d305.png">

Noted:
* x = Parameters
* 3 = Arguments

## Pydoc ##

### Pydoc ###

How to call pydoc use terminal:

<img width="220" alt="image1" src="https://user-images.githubusercontent.com/61875831/194763173-a6fa825c-d255-4a9f-8482-43eb30555678.png">

## File .txt ( Open, Read, and Close ) ##

### Open ###

If we want to open and read all contents in a file of type 'text-document', use functions `open` and `read`:

<img width="282" alt="image1" src="https://user-images.githubusercontent.com/61875831/194777161-2ebbbabc-deff-40e1-9cd7-3bed31538202.png">

### Read ### 

Read per line a file of type 'text document' use function `open` and `readline` (The readline() function will read per line starting from line 1 then line 2 and then line 3 and other lines):

<img width="299" alt="image1" src="https://user-images.githubusercontent.com/61875831/194777592-96136588-f053-43e4-80c5-e606bd364140.png">

### Close ### 

Close a file of type 'text document' use function `close`:

<img width="250" alt="image1" src="https://user-images.githubusercontent.com/61875831/194778039-9def0fc8-6524-4829-b106-abed5bc319c6.png">

