class Animal: 
  def __init__(self, name):
    self.name=name
  def eat (self):
    print("I can eat")
  def sleep (self):
    print("I can sleep")

class Dog(Animal):
  def __init__(self,name):
    Animal.__init__(self,name)

  def bark (self):
    print("I can bark")

class Cat(Animal):
  def __init__(self,name):
    Animal.__init__(self,name)
  def meow (self):
    print("I can meow")


dog=Dog("pop");
dog.bark();

cat=Cat("nop");
cat.meow();
