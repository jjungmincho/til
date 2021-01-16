# while

`while True:` -> 무한 루프

## break
```py
i = 0
for i in range(100):
  print(i)
  print("hello")
  print("funny")
  i = i + 1

  if i > 5:
    break
```
- This will print only 6 times of hello and funny due to break.

## continue
```py
i = 0
for i in range(3):
  print(i)
  print("hallo")
  print("funny")

  if i == 1:
    continue

  print("nice to meet u")
```
- This will print only hallo and funny except when i is 1.
- `continue` is used when you want to print out a special one in the certain circumstances 