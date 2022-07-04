# 0x0A. Python - Inheritance

* (0-lookup.py)[0-lookup.py] - A function that returns the list of available attributes and methods of an object:
  * Prototype: `def lookup(obj):`
  * Returns a `list` object
  * Not allowed to import any module

* (1-my_list.py)[1-my_list.py] - A class `MyList` that inherits from `list`:
  * Public instance method: `def print_sorted(self):` that prints the list, but sorted (ascending sort)
  * Assumes that all the elements of the list will be of type `int`
  * Not allowed to import any module

* (2-is_same_class.py)[2-is_same_class.py] - A function that returns `True` if the object is exactly an instance of the specified class; otherwise `False`:
  * Prototype: `def is_same_class(obj, a_class):`
  * Not allowed to import any module

* (3-is_kind_of_class.py)[3-is_kind_of_class.py] - A function that returns `True` if the object is an instance of, or if the object is an instance of a class that inherited from, the specified class ; otherwise `False`:
  * Prototype: `def is_kind_of_class(obj, a_class):`
  * Not allowed to import any module

* (4-inherits_from.py)[4-inherits_from.py] - A function that returns `True` if the object is an instance of a class that inherited (directly or indirectly) from the specified class ; otherwise `False`:
  * Prototype: `def inherits_from(obj, a_class):`
  * Not allowed to import any module

