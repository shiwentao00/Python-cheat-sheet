# Python-cheat-sheet
Python cheat sheet for daily work and coding interveiws for those not good at memorizing.

### 1. Sorting

To sort in-place:
```python
a = [2, 1, 3]
a.sort()
a.sort(reverse=True)
```
To return a sorted list:
```python
x = sorted(a)
x = sorted(a, reverse=True)
```

### 2 Hashset

Hashset in Python is implemented as ```set()```:
```python
a = set([1, 2, 3])
```
To add, remove, and empty the set:
```python
a.add(4)
a.remove(3)
a.clear()
```
Hashset is iterable,
```python
for x in a:
    print(x)
```
but it is not indexable. To index a hashset, convert it to list first:
```python
list(a)[0]
```
