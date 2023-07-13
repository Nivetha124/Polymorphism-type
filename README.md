# Polymorphism-type

Two type 
*   overloading
*   overriding
*   
# "OVERLOADING"
*  operator overloading
     + is a addition(integer)
     + is a concatenation(string)
       
# "Method overloading"
  $ methods name should be same
  $ arguments must be different
  eg:  add(),add(3,5),add(3,4,5)
  class Overload:
     def display(self,a,b)
        print(a,b)
  obj=Overload()
  obj.display(10,9)
  obj.display(1)

  # "OVERRIDING"
      *  Derived class override from the base class.
  # real time example:
      &   version2 override from the version1.
      &   A father have bike and son have cycle both have same transportation the son override from the father. So son have both cycle and bike.
     &    Many of the real world habits of a parent child can be overridden in nature.
  eg:
  class Shape:
    def __init__(self, name):
        self.name = name
    def area(self):
        pass
    def fact(self):
        return "I am a two-dimensional shape."
    def __str__(self):
        return self.name
class Square(Shape):
    def __init__(self, length):
        super().__init__("Square")
        self.length = length
    def area(self):
        return self.length**2
    def fact(self):
        return "Squares have each angle equal to 90 degrees.
class Circle(Shape):
    def __init__(self, radius):
        super().__init__("Circle")
        self.radius = radius
    def area(self):
        return pi*self.radius**2
a = Square(4)
b = Circle(7)
print(a)
print(a.fact())
print(b.fact())
print(a.area())
                                                           (OR)
   class version1:
      def button(self):
          print("colour red")
  class version2(version1):
      def button(self):
          print("colour blue")
  obj=version2()
  obj.button()
                                                            (OR)
  class Father:
     def Transportation(self):
         print("bike")
  class Son(Father):
     def Transportation(self):
         print("Cycle")
  obj=Son()
  obj.Transportation()


  
  
   
  
