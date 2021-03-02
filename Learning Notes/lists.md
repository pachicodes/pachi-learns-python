## Lists
Lists in Python are used to store ordered collections of itens.
A list can contain more than one data type and you can even make a list of lists

### List Method `.append()`
You can use the `append` method to add a element to the end of your list.

### Zip
You can create a new list, adding lists together with `zip`.

```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
list3 = zip(1, 2, 3, 4, 5, 6)
```

Note though, that if you print `list3` you won't get the print you are exepcting.
You have to turn the `zip` into a list first with `list()`.

### Range
The function `range` takes a single input, and generates numbers starting at 0 and ending at the number **before** the input.
So if you want your list to end at 10, you have to enter 11.

```python
range(11)
```

You can also change the number it starts on, adding it to the range method. The example bellow starts at 2.

```python
range(2, 11)
```

Last but not least, you can skip numbers with a third argument.

```python
range(2, 11, 2)
```

The example above will print `2, 4, 6, 8, 10`.

### Negative List Indices
You can use negative index to acess elements in relations to the end of the list.

### List Method `.count()`
You can search a list for how many times an item appears on it.

### Determining List Length with `len()`
Use `len()` to find out a list length.

### List Method `.sort()`
You can sort a list on numeric or alphabetic order with sort.
It DOES NOT create a new list, but modifies it.

### `sorted()` Function
This function creates a new list, sorting the contents of the original.

### List Slicing
You can slice a list, meaning, select what part of the list you want to sue to create a new list.
It automatically stars on index 0, unless you change it. The new lists goes until the second number -1.

```python
numbers = [0, 1, 2, 3]
numbers1 = numbers[1:3]
```

In the example above, `numbers1` would print `1, 2`.
