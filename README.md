# python-todo-list

* ❓ [list] a slicing of a list is a (shallow) copy of the original list. Change it will not change the original one.
* ✅ [dict] sort dict by values
```python
x = {'a':10, 'b':100, 'c':1}
sorted(x.items(), key=lambda x:x[1])
```
* ✅ add to list, dict, and set
```python
a = [1, 2, 3]
a.append(1000)

b = {1, 2, 3}
b.add(1000)

c = {'a':10, 'b':100, 'c':1}
c.update(x=1000)
```
