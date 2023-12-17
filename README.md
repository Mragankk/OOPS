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
stu= student("mragank",1) #object
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
- **POLYMORPHISM** : ability of object to take on many forms
   - ***method overloading***: same method but different parameters
```bash
def products(a,b):
   print(a*b)
def product (a,b,c):
   print(a*b*c)
```
  - ***operator overloading***: when operator used multiple times
- **INHERITANCE** : one class inherits the attributes and methods of another class
    - IN INHERTANCE, A PARENT CAN HOLD REFERENCE OF CHILD AND CAN ACCESS ONLY THOSE MEMBERS OF CHILD WHOSE SIGNATURE IS PROVIDED FROM PARENT TO 
           CHILD.
  - ***Method overridng***: virtual method of parent class rewritten in child class with same signature and different number of arguments
  - ***method hiding***: a method of parent class in parent class, rewritten in child class with same signature and different number of arguments
 








```
# a = 555
# print(a**2)
# print(type(a))
# b = str((a))
# print = (b)
# a="10"
# print(a)
# b=int(a)
# print(b)
# print(type(b))
# print("datatype of a is",type(a))
# also -> A = int(input(("enter your age:")))
# print(A+2)

# a=int(input("enter pehla number:")) 
# b=int(input("enter dusra number:"))
# print("the sum of a and b is", a+b) # SIMPLY ADDING TWO NUMBERS

# x = 91
# y=2
# print("the remainder when x divided by y is", x%y)  # to find remainder use '%' ie x/y 
# m=98
# n=45
# print(n>m)# check if number is greater or equal

# print(m>=m)
# F=int(input("enter first number:"))
# S=int(input("enter second number:"))
# print("averge of Fand E is",(F+S)/2)

# w=int(input("enter a no:"))
# print("squre of w is",w**2)

# a="hahahahah's"
# print(a)
# m=''' "mannu" '''
# print(m)

# print(''' MRAGANK'S      "MRAGANK"  ''')

# greetings='Good morning,'
# name=str(input("your name:"))
# print(greetings + name)

# M='MRAGANK'
# print(M[3]) # M variable ka 3 wala string text milega(count start from 0)
# print(M[6]) # m variable ka 6 wala text milega (starting from 0 and have length l-1)
# print(M[1:5])# M variable ke 1 se 4 tak chihye [note - aise m ":"ke baad wala no ke -1 tak milta hai ....mtlb vo include nahi hoga ]
# print(M[-1]) # negative indexing (last se 1 wala count karega and print karega)
# print(M[:5])
# print(M[1:])
# print(M[-3:-1])
# print(M[1:6:2]) # third wala mtlb hai usko exclude kar do ( 1 se 6 tak print karo lekin har 2 wale ko exclude kar do)[R print karega aur A skip karaga ,phir G print karega aur A skip phir N print aur bass yahi tak tha. ]

# bakwaas= 'hahaha lalala  wawaaaaaaawawawa hehehehe huhuuhu hue hue hue hue'
# print(len(m)) #length of string
# print(bakwaas.endswith("hue"))
# print(bakwaas.count('a'))
# print(bakwaas.count('e'))
# print(bakwaas.capitalize()) # first letter capital kar degi
# print(bakwaas.find('hue'))
# print(bakwaas.replace('hue','huee'))

# name=input("pls enter your  name: ")
# g= 'Good afternoon, '
# print(g+name)

# letter='Dear Mannu,\nyou are very nice guy.\nthanks!!'
# print(letter)
# letter1='Dear Mannu,\n\'you are very nice guy.\n\'thanks!!'
# print(letter1)
# letter2='Dear Mannu,\n\tyou are very nice guy.\nthanks!!'
# print(letter2)

# list=[1,56,89,45,22,65,0,'mannu'] #list [], is mutable
# print(list[5])
# list[2]= 99 # change 2 entry as 99
# print(list) # list is changed
# print(list[0:3]) # list slicing
# print(list[0:2:2])
# l1=[5,8,9,0]
# l2=[4,5,9,5]
# print(l1+l2)
# print([l1[1],l2[0]])

# l=[1,5,0,1,1,19,7,3,5,55,88,11,55,12]

# print(l)
# (l.sort()) #sort the list 
# print(l)
# (l.append(100)) # adds to the list at last
# print(l)
# (l.remove(19)) # removes 9 in list
# print(l)
# (l.pop(5)) # removes 5th element from list
# print(l)
# l.reverse() # reverse the whole list
# print(l)
# (l.insert(4,5444)) #insert 5444 on 4th position of list
# print(l)
# cout=(l.count(1)) # count no of 1 in list
# print(cout)
# inx=l.index(11) # find the position of 12 in list
# print(inx)

# T=(8,4,5,9,2,0,8,81) # tuple() in brackets m likhte hai, immutable
# print(T)
# T1=(1,) # correct way to write a tuple ("," lagake)
# print(T1)
# cout=T.count(8)
# print(cout)
# ind=T.index(0)
# print(ind)

# l=[]
# first=int(input("enter marks of first student:"))
# l.append(first)
# second=int(input("enter marks of second student:"))
# l.append(second)
# third=int(input("enter marks of third student:"))
# l.append(third)
# fourth=int(input("enter marks of fourth student:"))
# l.append(fourth)
# fifth=int(input("enter marks of fifth student:"))
# l.append(fifth)
# sixth=int(input("enter marks of sixth student:"))
# l.append(sixth)
# print("marks of 6 students are",l)

# f1=input("enter fruit no 1: ")
# f2=input("enter fruit no 2: ")
# f3=input("enter fruit no 3: ")
# f4=input("enter fruit no 4: ")
# f5=input("enter fruit no 5: ")
# f6=input("enter fruit no 6: ")
# fav_fruit_list=[f1,f2,f3,f4,f5,f6]
# print(fav_fruit_list)

# m=[4,8,6,7,2]
# print("sum of m is:", m[0]+m[1]+m[2]+m[3]+m[4])
# print(sum(m))
# t=(2,5,7,6)
# print(t[0]+t[1]+t[2]+t[3])
# print(sum(t))
# print(len(t))

# D1={'mannu':20, 'fruit':'mango', 'sports':'cricket',
#     4:'2+2' , 'marks':[8,5,7,6], 'T':(9,8,7), 'D2':{'father':'Subodh'}}
# print(D1['marks'])
# print(D1['D2']['father'])
# D1['fruit']='orange'
# print(D1)
# print(D1.keys())
# print(D1.values())
# print(D1.items())  # tuple form m bana deta hai taaki iterate karne m easy ho
# newD={"rajat":"friend"}
# D1.update(newD)
# print(D1)
# print(D1.get('mannu'))
# print(D1.get('D2'))

# hindi_dict={'clothes':'kapde', 'fan':'pankha','laughing':'hasna','sleep':'sona','box':'dabba','punjal':'bhensss'}
# print('options for dictionary are:',hindi_dict.keys())
# guess=input("enter english word from options: ")
# print("meaning of this english word is:",hindi_dict[guess])

# S={1,5,8,7,4,'mannu'} #sets - non repeating elements
# print(S)
# S1={}
# print(type(S1))
# Empty_set= set() # to create empty set
# print(Empty_set)

# print(type(S))
# print(type(Empty_set))
# important baat - set m list add nahi kar sakte lekin tuple add kar sakte hai
# S.add[45,6,2] #yeh work nahi karega
# S.add((99, 54))  # yeh add ho jayega 
# print(S)

# sala={1,5,4,6,5}
# print(type(sala))
# sala.remove(1)
# print(sala)
# print(len(sala))
# print(sala.pop())

# N1=int(input("enter 1st number\n"))
# N2=int(input("enter 2nd number\n"))
# N3=int(input("enter 3rd number\n"))
# N4=int(input("enter 4th number\n"))
# N5=int(input("enter 5th number\n"))
# N6=int(input("enter 6th number\n"))
# S={N1,N2,N3,N4,N5,N6}
# print(S)

# fd={}
# raj=input("rajat's fav language is\n")
# aka=input("akaash's fav language is\n")
# sak=input("sakshi's fav language is\n")
# jai= input("jaid's fav language is\n")   
# fd={'rajat':raj,'akash':aka,'sakshi':sak,'jaid':jai}
# print(fd)


# x=int(input("enter a number:"))
# if(x>18):
#   print("yes")
# else:
#  print("no")


# n1=int(input("enter 1 no:"))
# n2=int(input("enter 2 no:"))
# n3=int(input("enter 3 no:"))
# n4=int(input("enter 4 no:"))

# if(n1>n2):
#     b1=n1
# else:
#     b1=n2
# if(n3>n4):
#     b2=n3
# else:
#     b2=n4
# if(b1>b2):
#     print(str(b1)+" is the greatest number")
# else:
#     print(str(b2)+" is the greatest number") 

# maths=int(input("marks of maths:"))
# chem=int(input("marks of chem:"))
# phys=int(input("marks of phys :"))
# if(maths>33):
#      if(phys>33):
#          if(chem>33):
#              if((maths+chem+phys)>=120):
#               print("pass")
# else:
#  print("fail")

# x=input("enter your name\n")
# if(len(x)>=10):
#     print("your name has 10 letters")
# else:
#     print("your name do not have 10 letters")

# msg=input("enter the text\n")
# if("click here"in msg ):
#     print("spam hai bhai ")
# elif("subscribe now"in msg):
#     print("spam hai bhai")
# elif("money" in msg):
#     print("spam hai bhai")
# else:
#     print("koi dikkt wali baat nahi hai")

# x=int(input("enter your marks to get grade\n"))

# if(x<=100 and x>90):
#     print("you got grade 'EX'")
# if(x<=90 and x>80):
#     print("A")
# if(x<=80 and x>70):
#     print("grade 'B")
# else:
#     print("fail ho gaya bhai")


# i=0
# while(i<101):
#     print(i)
#     i=i+1

# print("done")

# i=1
# while(i<51):
#     print(i)
#     i=i+1

# i=0
# l=['hello','heyy','hii','namaste','helo','howdie']
# while i<len(l):                  # while loop
#       print(l[i])
#       i=i+1 

# i=0
# l=['hello','heyy','hii','namaste','helo','howdie']
# for item in l:                 # for loop
#       print(item)
#       i=i+1

# for i in range(-15,8):
#     print(i)
     
# for i in range(-15,8,2):      # 2  2 k gap aa jayega
#     print(i)

# for i in range(100):
#     if i==45:
#         continue
#     print(i)
#     if i==47:
#         break

# for i in range(100):
#     if i==45:
#         continue
#     if i==46:
#         print('hahha')
#     print(i)
#     if i==47:
#         break

# i=0
# for i in range(1,11):
#    print("9 x" ,i ,'=', 9*i)
#    i=i+1

# l=['rohan','vickey' , 'sakshi' , 'sunny','harry', 'raman','saksham','manish' ]

# for item in l:
#     if('s' in item):
#       if(item[0]=='s'):
#        print("hello ",item, ' you are so adorable')


# num=int(input("enter number: "))
# factorial=1
# for i in range(1, num+1):
#     factorial = factorial*i
# print(f"the facorial of {num} is {factorial}")


# n = int(input("Enter a number: "))
# sum = 0
# i = 1
# while i <= n:
#     sum += i
#     i += 1
# print(f"The sum of the first {n} natural numbers is {sum}.")

# def add(num): # Sum of first n natural numbers
#  if num == 0:
#   return 0
#  else:
#   return num + add(num-1)
# add(10)


# def marks(meremarks):
#     print("my marks are", meremarks)
# marks(77)
# marks(88)
# marks(200000000000000000000)
    
# def fruits(fal):
#     print("my fav fruits are", fal)
# fruits("'banana','mango'")

# def fnc(name="user"):
#     print(f"thank you  {name}  for using this code")
# fnc()

# l="hsajdb skjfsa asjsakj bas asjbfs"
# for i in l:
#     print(i)
# for i in enumerate(l):
#     print(i)
# l="asjbfiasbkjsabfasvskjbsakj"
# l=[i for i in  l]
# print(l)

# t1=(99,54,45)
# t2=(1,2,3)
# swap=t1
# t1=t2
# t2=swap
# print("t1-",t1,"&"," t2-",t2)

# def m(n1,n2,n3):
#     if(n1>n2):
#       if(n1>n3):
#         return n1
#       else:
#         return n3
#     if(n2>n3):
#        return n2
#     else:
#           return n3
    
# lala=m(5,8,13)
# print(lala)

# def lambai(inches):
#     return inches* 2.54
# cm=56
# la=lambai(cm)

# print(la)

# file=open('haa.txt','r')
# data=file.read()
# print(data)
# file.close
```
 
