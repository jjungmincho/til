# dict()
`dict()` = { key: value }

```py
x = dict()
y = {}

print(x)
print(y)
```
```py
z = {
    "name": "jess",
    "age": 12,
}

print(x["name"])
print(x["age"])

#jess
#12
```
```py
x = {
  0: "jess",
  1: "hello",
  "age": 20,
}

print(x.keys())
print(x.values())

#dict_keys([0, 1, 'age'])
#dict_values(['jess', 'hello', 20])

for key in x:
  print("key: " + str(key))
  print("value: " + str(x[key]))

#key: 0
#value: jess
#key: 1
#value: hello
#key: age
#value: 20
```

* `dict` can assign the value