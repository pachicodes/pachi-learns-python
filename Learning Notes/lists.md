## Lists
Lists in Python are used to store ordered collections of itens.
A list can contain more than one data type and you can even make a list of lists

### List Method .append()
You can use the append method to add a element to the end of your list.

### Zip
You can create a new list, adding lists together with **zip**. 
```
list1 = [1, 2, 3]
list2 = [4, 5, 6]
list3 = zip(1, 2, 3, 4, 5, 6)
```
Note though, that if you print list3 you won't get the print you are exepcting.
You have to turn the zip into a list first with list()

### Range
The function range takes a single input, and generates numbers starting at 0 and ending at the number **before** the input.
So if you want your list to end at 10, you have to enter 11.
```
range(11)
```
You can also change the number it starts on, adding it to the range method. The example bellow starts at 2.
```
range(2, 11)
```

Last but not least, you can skip numbers with a third argument.

```
range(2, 11, 2)
```

The example above will print 2, 4, 6, 8, 10
