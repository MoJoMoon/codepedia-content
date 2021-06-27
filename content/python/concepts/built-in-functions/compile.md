---
Title: "compile()"
Subjects:
  - "Computer Science"
  - "Data Science"
Tags:
  - "Functions"
  - "Methods"
  - "Strings"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/computer-science"
  - "https://www.codecademy.com/learn/paths/data-science"
---

## Definition

Returns a runnable code object created from a `string`.

## Syntax

```py
abs(n)
```

## Example 1

Use `compile()` to return the absolute value of `-6.5`:

```py
x = compile('print(55)\nprint(88)', 'test', 'exec')
exec(x)
```
