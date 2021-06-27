---
Title: "classmethod()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Functions"
  - "Methods"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/data-science"
---

## Definition

Converts a given function into a class method.

## Syntax

```py
abs(n)
```

## Example 1

Use `classmethod()` to return the absolute value of `-6.5`:

```py
class Student:

    # create a variable
    name = "Codecademy"

    # create a function
    def print_name(obj):
        print("The name is : ", obj.name)

# create print_name classmethod
# before creating this line print_name()
# It can be called only with object not with class
Student.print_name = classmethod(Student.print_name)

# now this method can be called as classmethod
# print_name() method is called a class method
Student.print_name()
```

## Example 2

Use `classmethod()` to return the absolute value of the `numbers` list:

```codebyte/python
numbers = [-19.2, 27.3, 48, -115, 302.7, -421, -2011]

print([abs(number) for number in numbers])
```
