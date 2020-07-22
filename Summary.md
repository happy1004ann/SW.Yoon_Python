## 01 Reference count와 Garbage collection
Reference count가 0이 되면 메모리에서 없어짐
## 02 Mutable object와 Immutable object
>Mutable : 'list', 'dict'
>>Immutable : 'tuple', 'str'

  id(obj, /)

  >>> r = [1, 2]
  >>> r += [3, 4]
  >>> r
  [1, 2, 3, 4]

  >>> s = (1, 2)
  >>> s += (3, 4)
  >>> s
  (1, 2, 3, 4)



## 03 Deep copy와 Shallow copy
## 04 List comprehension