Integers, floating point numbers and complex numbers fall under Python numbers category. 

They are defined as int, float and complex classes in Python.

We can use the type() function to know which class a variable or a value belongs to. 

Similarly, the isinstance() function is used to check if an object belongs to a particular class.

### Integer

`a = 5`{{execute}}

`print(a, "is of type", type(a))`{{execute}}

### Float
`a = 2.0`{{execute}}

`print(a, "is of type", type(a))`{{execute}}

### Boolean
`a = 1+2j`{{execute}}

`print(a, "is complex number?", isinstance(1+2j,complex))`{{execute}}

Integers can be of any length, it is only limited by the memory available.

A floating-point number is accurate up to 15 decimal places. 

Integer and floating points are separated by decimal points. 1 is an integer, 1.0 is a floating-point number.


