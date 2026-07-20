# python-learning-notes
Repository for https://replit.com/@chilhate/PythonBasics
print('hello world')
print('hello world')
print("hello, vaishali!")
print("welcome to python with codewithherry")
#hey, please dont remove this line
#for escape sequence character, we use backslash'\n'
print("hey i am a good boy\nand this viewer is also a good boy/girl")
#author: vaishali
#courseteacher: harry
#date: 31/01/2026
#for double quote we use backslash
print('hey i am a \'good boy\' and this viewer is also a good boy/girl')
# this is a single line comment
'''comment in multiple lines
text
multiple'''
#print statement example
print("hey", 6, 7, sep="~")
print("vaishali")
print("hey", 6, 7, sep="~", end="009")
print("vaishali")
print("hey", 6, 7, sep="~", end="009\n")
print("vaishali")
#variables and data types
a = 1234
print(a)
b = "vaishali"
print(b)
c = True
print(c)
d = 1.1
print(d)
e = complex(4, 9)
f = "none"
a1 = 9
print(a + a1)
print("the type of a is", type(a))
print("the type of b is", type(b))
print("the type of c is", type(c))
print("the type of d is", type(d))
print("the type of e is", type(e))
print("the type of f is", type(f))
#list=ordered collection of data items, (items enclosed in square brackets) and they are changeable and can repeat
list1 = [8, 2.3, [-4, 5], ["apple", "banana"]]
print(list1)
#tuple=ordered collection of data items, (items enclosed in round brackets) and they are unchangeable and can repeat
tuple1 = (("parrot", "sparrow"), ("lion", "tiger"))
print(tuple1)
#dictionary=unordered collection of data containing key value pairs, (items enclosed in curly brackets) and they are changeable and cannot repeat
dict1 = {"name": "vaishali", "age": 20, "canvote": True}
print(dict1)
#opertors
a = 15
b = 7
print("a=15")
print("b=7")
ans1 = a + b
print("addition of a and b is", ans1)
ans2 = a - b
print("subtraction of a and b is", ans2)
ans3 = a * b
print("multiplication of a and b is", ans3)
ans4 = a / b
print("division of a and b is", ans4)
ans5 = a % b
print("modulus of a and b is", ans5)
ans6 = a**b
print("exponential of a and b is", ans6)
ans7 = a // b
print("floor division of a and b is", ans7)
#typecasting
#explicit typecasting
string = "20"
number = 6
string_number = int(string)
sum = number + string_number
print("sum of both the numbers is:", sum)
#implicit typecasting
c = 2.9
d = 7
print(c + d)
print("the type of c is", type(c))
print("the type of d is", type(d))
print("the type of c+d is", type(c + d))
#input function
# a = input("enter your name:")
# print("my name is", a)

# x = input("enter first number: ")
# y = input("enter second number: ")
# print(x + y)
# print(int(x) + int(y))
# print(int(x) - int(y))
# print(int(x) * int(y))
# print(int(x) / int(y))
# print(int(x) % int(y))
# print(int(x) ** int(y))
# print(int(x) // int(y))
#strings
#single line string
name = "vaishali"
print("hello, " + name)
#multiline string (using triple quotes)
rohan = '''he said,hi vaishali
i am good
i want to eat an apple'''
print(rohan)
#accessing characters of a string
print(name[0])
print(name[1])
print(name[2])
print(name[3])
print(name[4])
print(name[5])
print(name[6])
print(name[7])
#for loop to access characters of a string
print("lets use a for loop\n")
for character in name:
  print(character)
#strings slicing and operations in python
fruit = "mango"
len1 = len(fruit)
print(len1)
print(fruit[0:4])
print(fruit[1:4])
print(fruit[:5])
print(fruit[0:-3])
#nagative slicing
print(fruit[-3:-1])
print(fruit[len(fruit) - 3:len(fruit) - 1])  #[5-3:5-1]=[2:4]
#[2:4] means 2,3] (n-1)

#string methods
#strings are immutable
#upper()
a = "vaishali"
print(a.upper())
#lower()
print(a.lower())
#rstrip()
b = "sunflower!!!!!!!"
print(b.rstrip("!"))
c = "!!!mango!!!!"
print(c.rstrip("!"))
#replace()
d = "silver spoon"
print(d.replace("sp", "h"))
print(d.replace("spoon", "jar"))
#split()
e = "vaishali is a good girl"
print(e.split(" "))
#capitalize()
f = "basics of python"
print(f.capitalize())
#center()
g = "welcome to python"
print(g.center(50))
print(g.center(25))
print(g.center(30))
print(len(g))
print(g.center(34))
#count
h = "she sells sea shells on the sea shore"
print(h.count("s"))
print(h.count("sea"))
#endswith()
j = "welcome to the python!!!"
print(j.endswith("!"))
#output()
print(j.endswith("to", 4, 10))
print(j.endswith("to", 5, 11))
#find()
k = "his name is den. den is a good boy"
print(k.find("is"))
print(k.find("den"))
print(k.find("honest"))
#index()
print(k.index("is"))
#isalnum()
l = "welcome009"
print(l.isalnum())
m = "welcome to python"
print(m.isalnum())
o = ("Welcome to Python")
print(o.isalnum())
#isalpha()
n = "welcome"
print(n.isalpha())
p = "welcome009"
print(p.isalpha())
#islower()
q = "hello world"
print(q.islower())
r = "HELLO WORLD"
print(r.islower())
#isprintable()
s = "we wish you a merry christmas"
print(s.isprintable())
t = "we wish you a merry christmas\n"
print(t.isprintable())
#isspace()
u = " "
print(u.isspace())
u = "blank"
print(u.isspace())
#istitle()
v = "world health Organization"
print(v.istitle())
v = "World Health Organization"
print(v.istitle())
#isupper()
#startswith()
w = "python is a interpreted language"
print(w.startswith("python"))
#swapcase()
x = "Python Is A interpreted LanguaGe"
print(x.swapcase())
#title()
y = "tuesdays with morrie"
print(y.title())
#if else statement

# a=int(input("enter your age: "))
# print("your age is:",a)
# if (a>18):
#   print("you can drive")
# else:
#   print("you cannot drive")
#elif statement

# num=int(input("enter the value of num:"))
# if (num < 0):
#   print("number is negative")
# elif (num == 0):
#   print("number is zero")
# elif (num == 999):
#   print("number is special")
# else:
#   print("number is positive")
#nested if statement
num = 15
if (num < 0):
  print("number is negative")
elif (num > 0):
  if (num <= 10):
    print("number is between 1-10")
  elif (num > 10 and num <= 20):
    print("number is between 11-20")
  else:
    print("number is greater than 20")
else:
  print("number is zero")
#excersice
import time

timestamp = time.strftime('%H:%M:%S')
print(timestamp)
timestamp = time.strftime('%H')
print(timestamp)
timestamp = time.strftime('%M')
print(timestamp)
timestamp = time.strftime('%S')
print(timestamp)

#good morning excersice

a = "good morning"
b = "good afternoon"
c = "good evening"
timestamp = time.strftime('%H:%M:%S')
print(timestamp)
if (timestamp > "05:00:00" and timestamp < "12:00:00"):
  print("good morning")
elif (timestamp > "12:00:00" and timestamp < "15:00:00"):
  print("good afternoon")
else:
  print("good evening")

#match case statement

# x=int(input("enter the value of x:"))
# match x:
#   case 0:
#     print("x is zero")
#   case 4:
#     print("case is 4")
#   case _ if x!=90:
#     print(x,"is not 90")
#   case _ if x!=80:
#    print(x,"is not 80")
#   case _:
#     print(x)
#for loops
name = "vaishali"
for i in name:
  print(i)
  if (i == "a"):
    print("this is something special")
colors = ["white", "yellow", "pink", "blue", "green"]
for color in colors:
  print(color)
  for i in color:
    print(i)
#range()
for k in range(5):
  print(k)
for k in range(1, 10):
  print(k)
for k in range(1, 12, 3):
  print(k)

print("-----------")
#while loop
i = 0
while (i < 3):
  print(i)
  i = i + 1
print("done with the loop")
print("-----------")
#decrementing while loop
count = 5
while (count > 0):
  print(count)
  count = count - 1
print("-----------")
#else with while loop
count = 5
while (count > 0):
  print(count)
  count = count - 1
else:
  print("i am inside else")
#do while loop
# while True:
#   number = int(input("enter a positive number:"))
#   print(number)
#   if not number > 0:
#     break


#break statement
for i in range(12):
  if(i==10):
    break
  print("5*",i+1,"=",5*(i+1))
print("break the loop")
print("-----------")
#continue statement
for i in range(12):
  if(i==10):
    print("skip the iteration")
    continue
  print("5*",i,"=",5*i)
print("-----------")
#functions
a=9
b=8
def calculateGmean(a,b):
  mean = (a*b)/(a+b)
  print(mean)
c=8
d=74
def isGreater(a,b):
  if(a>b):
    print("first number is greater")
  else:
    print("second number is greater")
isGreater(a,b)   
calculateGmean(a,b)
isGreater(c,d)
calculateGmean(c,d)
# def isGreate (a,b):
#   pass
#( it means that we will write the code later)
# Function arguments 
# default arguments
def name(fname, mname="Jhon", lname="Whatson"):
  print("Hello,", fname,mname,lname)
name("amy")
name("lisha","ted")
name(fname="amy",lname="jackson")
#keywords arguments
def name(fname,mname,lname):
  print("hello,",fname,mname,lname)
name(mname="nitin",lname="mukesh",fname="neil")
#required arguments
def name(fname,mname,lname):
  print("hello,",fname,mname,lname)
# name("tina","roy"),require one more value
name("tina","roy","whatson")
#variable length arguments
print("------------")
#Lists
list1=[1,2,3,4,5,6,7,8,9]
list2=["white","black","pink","red","blue","yellow"]
print(list1)
print(type(list1))
print(list2)
print(type(list2))
#list index
print(list1[0])
print(list1[1])
print(list1[2])
print(list1[3])
print(list2[0])
print(list2[1])
print(list2[2])
print("-----")
#negative index
print(list2[-3])
print("-------")
#positive index
print(list2[len(list2)-3])
print("-------")
print(list2[3])
#check whether an item is present in the list
if 6 in list1:
  print("yes")
else:
  print("no")

if "6" in list1:
  print("yes")
else:
  print("no")#because here "6" is used as string and we stored 6 as an integer in our list
#same thing applies for string
if "whi" in "white":
  print("yes")
else:
  print("no")
#range of index
#listName[start:end:jumpindex]
print(list2[2:5])
print(list2[-4:-1])
print(list1)
print(list1[1:8])
print(list1[1:8:2])
print("------")
#list comprehension
lst=[i for i in range(7)]
print(lst)

names=["Milo","Sarah","Bruno","Rosa","Anastasia"]
namewith_o=[item for item in names if"o" in item]
print(namewith_o)

namewith_o=[item for item in names if (len(item)>4)]
print(namewith_o)

#list methods
colors=["voilet","green","indigo","green"]
num=[4,5,2,5,3,7,2,5,6,3,8,9,]
#sort
colors.sort()
print (colors)
num.sort()
print(num)

#reverse
colors.reverse()
print(colors)
num.reverse()
print(num)

#index
print(colors.index("green"))
print(num.index(3))#????

#count
print(colors.count("green"))
print(num.count(3))

#copy
newlist=colors.copy()
print(colors)
print (newlist)

newlist=num.copy()
print(num)
print(newlist)

#append
colors.append("white")
print(colors)
num.append(6)
print(num)
#insert
colors.insert(1,"pink")
print(colors)
#extend()
rainbow=["pink","white","black","yellow"]
colors.extend(rainbow)
print(colors)

#concatenating two list
colors2=["olive green","sea blue","gray"]
print(colors+colors2)

print("----------")
#tuples
