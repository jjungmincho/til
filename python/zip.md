# zip

If we wanted to create a list of lists that paired each name with a height, we could use the command `zip`. `zip` takes two (or more) lists as inputs and returns an object that contains a list of pairs. Each pair contains one element from each of the inputs.

```py
names = ['A', 'B', 'C', 'D']
numbers = [10, 20, 30, 40]

names_and_numbers = zip(names, numbers)
print(names_and_numbers)
# <zip object at 0x7f1631e86b48>

print(list(names_and_numbers))
# [('A', 10), ('B', 20), ('C', 30), ('D', 40)]

```