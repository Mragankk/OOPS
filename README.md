# OOPS - Object Oriented Programming System
- important components
1. **class** - defines a set of data elements and methods (attributes and behaviours)
  ``` bash
     class students:
      //members
  ```
**constructor**- special method used to intialize fields of object   
 ```bash
class students:
   def __init__(self,name,class_) : 
    self.name = name
    self.class_ = class_ #data members

   def stuc(self):
       print(self.name,"is in class", self.class_) #method

```
2. **object** - allows to use real entities of class
```bash
stu = student("mragank",1) #object
stu.stuc()
```
   i. static binding
   ii. dynamic binding
   
3.**reference**- used to refer to an object ex `stu` in `stu= Student("mragank",1)`
- **full code**
```bash
class Students:
   def __init__(self,name,class_) : 
    self.name = name
    self.class_ = class_ #data members

   def stuc(self):
       print(self.name,"is in class", self.class_) #method
stu = student("mragank",1) #object
stu.stuc()
```
## Pillars of OOPs

- **ENCAPSULATION** : binding of methods in a single unit
- **ABSTRACTION** : a process of handling complexity by hiding unnecessary informatiion from the user
  - ***private*** : accessibile only withim the class
  - ***protected*** : accessible within class or child class
  - ***public*** : can be used by the object or inherited class
- **POLYMORPHISM** : 

