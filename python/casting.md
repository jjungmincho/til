# casting
Casting is when you convert a variable value from one type to another. This is, in Python, done with functions such as `int()` or `float()` or `str()` . A very common pattern is that you convert a number, currently as a string into a proper number.

- The `int()` method returns an integer object from any number or string.
```py
x = int(3.5)
print(x)
#3
```

- The `float()` method returns a floating point number from a number or a string.
```py
x = float(3)

print(x)
#3.0
```

- The `str()` function converts a specified value to a string data type.
```py
a = 10
print(a)
#10

print(type(a))
#<class 'int'>

b = str(a)
print(b)
#10

print(type(b))
#<class 'str'>

```

## Reference
[Peterbe.com](https://www.peterbe.com/plog/interesting-casting-in-python#:~:text=Casting%20is%20when%20you%20convert,string%20into%20a%20proper%20number.)

[Programize](https://www.programiz.com/python-programming/methods/built-in/float)

[w3school](https://www.w3schools.com/python/ref_func_int.asp)

[Quora](https://www.quora.com/What-is-STR-in-Python)