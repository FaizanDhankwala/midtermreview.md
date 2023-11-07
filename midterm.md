1.(1) Consider the following code.

If it runs without an error, write down the output.

If it causes an error, write down what error it is. 

 

import math

radius = -20

if radius >= 0:

    area = radius * radius * math.pi

print(area)

Answer: syntax error

2) Fill in the blanks from the following code.

```
a=[1, 2, 3, 4, 5]
b=a 
b[ 1 ] = 7 
print(a)
```
# What is output? 
The output is [1,7,3,4,5]



Write a function which takes a list as an argument and removes any duplicates in the list. Do not change the order of the remaining items in the list.

[please use Preformatted font when writing this code]

Your Answer:
def fun(alist):
  blist=[]

  for item in alist:
    if not item blist:
      blist.append(item)
    return blist




---------------------------------------------------
class Test:
  def __init__(self, n = 1, m = 2.0):
    if n < 0: 
      self.__a = n 
    else:
      self.__a = -n

    if m > 0:
      self.__b = m
    else:
      self.__b=-m

  def __str__(self):
      return f"{self.__a}:{self.__b}"

  def getA(self):
      return self.__a

  def getB(self):
      return self.__b
      
    
=========== main.py ============
## Fill out below so that main.py can load the Test class
From sample import Test



t1 = Test()
t2 = Test(-4.8)
t3 = Test(7, -3)

What is the output of the following code? Fill out the blank.

print(t1)

youre calling your constructor.

-1:2.0

print(t2)

Answer = 
-4.8:2.0

print(t3)

Answer 



The following code shows a definition of a Fraction class. 

 

class Fraction:
  # Fraction constructor
     def __init__(self,top,bottom):
         self.__num = top
         self.__den = bottom

     def __str__(self):
         return str(self.__num)+"/"+str(self.__den)

     def __sub__(self,otherfraction):
        newnum = self.__num*otherfraction.__den - \
                      self.__den*otherfraction.__num
        newden = self.__den * otherfraction.__den
        return Fraction(newnum,newden)

This program will cause an error for the following code.

 

f1 = Fraction(1,2)

print(1-f1)

 

(1) Write a python overloading operator in the Fraction class so that print(1-f1) can perform 1-1/2.



(2)After the implementation of overloading operator, what is the output of print(1-f1)?


(Note: This is an essay question. When you answer, please answer to all sub-questions)


def __rsub__(self, otherfraction):
  #if otherfraction is integer

 
