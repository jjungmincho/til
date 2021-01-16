# class

class == 빵틀
object == 빵 
*object == instance*

```py
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def say_hello(self, to_name):
    print("hello " + to_name + " I am " + self.name)
  
  def introduce(self):
    print("my name is " + self.name + " and I am " + str(self.age) + " age")

jess = Person("jess", 20)
jess.introduce()

class Police(Person):
  def arrest(self, to_arrest):
    print("you are arrested, " + to_arrest)

class Programmar(Person):
  def program(self, to_program):
    print("What to make next? I should make: " + to_program)

jess = Person("jess", 20)
jenny = Police("jenny", 25)
micheal = Programmar("micheal", 30)

jenny.introduce()
jenny.arrest("jess")
micheal.introduce()
micheal.program("email client")
```

## Reference
[YouTube: Finish Python in 1 hour by Teccboi Wonie](https://www.youtube.com/watch?v=M6kQTpIqpLs&t=4589s&ab_channel=TeccboiWonie)