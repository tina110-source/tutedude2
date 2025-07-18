# assignment 3

#task 1
def factorial(n):
   if(n<2):
     return 1
   else:
      return= n * factorial(n-1) 
result= factorial(3)
print(result)

# task 2
from math import *
n1= int(input("enter a number"))
print("square root",sqrt(n1))
base= e
print('logarithm', log(n1,base))
n1_radians= radians(n1)
print("sine",sin(n1_radians))
