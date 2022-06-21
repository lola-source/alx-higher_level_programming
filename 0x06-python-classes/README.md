#0x06. Python - Classes and Objects

**[0-square.py](./0-square.py)** Write an empty class Square that defines a square:
	-You are not allowed to import any module
**[1-square.py](./1-square.py)** Write a class Square that defines a square by: (based on 0-square.py)
	-Private instance attribute: size
	-Instantiation with size (no type/value verification)
	-You are not allowed to import any module
**[2-square.py](./2-square.py)** Write a class Square that defines a square by: (based on 1-square.py)
	-Private instance attribute: size
	-Instantiation with optional size: def __init__(self, size=0):
	-size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
	-if size is less than 0, raise a ValueError exception with the message size must be >= 0
	-You are not allowed to import any module
**[3-square.py](./3-square.py)** Write a class Square that defines a square by: (based on 2-square.py)
	-Private instance attribute: size
	-Instantiation with optional size: def __init__(self, size=0):
	-size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
	-if size is less than 0, raise a ValueError exception with the message size must be >= 0
	-Public instance method: def area(self): that returns the current square area
	-You are not allowed to import any module
**[4-square.py](./4-square.py)** Write a class Square that defines a square by: (based on 3-square.py)
	-Private instance attribute: size:
	-property def size(self): to retrieve it
	-property setter def size(self, value): to set it:
	-size must be an integer, otherwise raise a TypeError exception with the message size must be an integer
	-if size is less than 0, raise a ValueError exception with the message size must be >= 0
	-Instantiation with optional size: def __init__(self, size=0):
	-Public instance method: def area(self): that returns the current square area
	-You are not allowed to import any module
