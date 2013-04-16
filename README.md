vivienzou
=========
#This is a program to compute the sin, cos and tan based on 2 given sides by users.
#the code is here:

def f(a,b):
  
  c = (a**2+b**2)**0.5
  
  sinb = b/c
  
  cosb = a/c
  
  tanb = a/b

  cosa = sinb
  
  sina = cosb
  
  tana = 1/tanb

  print("This program is working for Trig functions given by 2 sides a and b")
  
  print("The sin, cos and tan of alpha bounded by side b and c, in order, is")
  
  print(sinb, cosb, tanb)

  print("The sin, cos and tan of Beta bounded by side a and c, in order, is")
  
  print(sina, cosa, tana)

#Below is a examples:

f(3,4)

This is a program is working for Trig functions given by 2 sides a and b

The sin, cos and tan of alpha bounded by side b and c, in order, is

0.8 0.6 0.75

The sin, cos and tan of Beta bounded by side a and c, in order, is

0.6 0.8 1.33333333333333333333
