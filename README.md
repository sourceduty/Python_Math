## Python_Math

🧮 Formulas and expressions for mathematical calculations using Python.

Created by Sourceduty.

#

## Addition 
```
a = 88
b = 103

print(a + b)
```
#

## Float
```
e = 5.5
f = 2.5

print(e + f)
```
#

## Subtraction
```
g = 75.67
h = 32

print(g - h)
```
#

## Multiplication
```
k = 100.1
l = 10.1

print(k * l)
```
#

## Division
```
m = 80
n = 5

print(m / n)
```
#

## Modulo

The % operator is the modulo, which returns the remainder rather than the quotient after division. This is useful for finding numbers that are multiples of the same number, for example.
```
o = 85
p = 15

print(o % p)
```

To break this down, 85 divided by 15 returns the quotient of 5 with a remainder of 10. The value 10 is what is returned here because the modulo operator returns the remainder of a division expression.

#

## Powers

The ** operator in Python is used to raise the number on the left to the power of the exponent of the right. That is, in the expression 5 ** 3, 5 is being raised to the 3rd power. In mathematics, we often see this expression rendered as 5³, and what is really going on is 5 is being multiplied by itself 3 times. In Python, we would get the same result of 125 by running either 5 ** 3 or 5 * 5 * 5.

```
s = 52.25
t = 7

print(s ** t)
```
#

## Area and Perimeter of a Rectangle

Area of a Rectangle
```
a*b
```
#

Perimeter of a Rectangle
```
2*(a +b)
```
```
a = 2
b = 3
area = a*b
perimeter = 2 * (a+b)
print(area) #printing the area
print(perimeter)#printing peri
```
#

## Area of a Circle

```

# Import math Library 
import math 
 
# radius of the circle
r = 4

# value of pie
pie = math.pi
 
# area of the circle
print(pie * r * r)
```
#

## Tau is defined as the ratio of the circumference to the radius of a circle. 

The math.tau constant returns the value tau: 6.283185307179586.

```
# Import math Library 
import math 
 
# Print the value of tau 
print (math.tau)
```
#

## Odd or Even

It’s very easy to find if a number is even or odd. Just apply the modulus operator that would give you the remainder of the division.

If the reminder is one, then it is odd

if the reminder is zero, then it is even

```
a = 6
b = 2
c = a%b
print(c)
a = 7
b = 2
c = a%b
print(c)
```
#

## Symbolic Computations

from sympy import Symbol, symbols
```
# define a symbol
X = Symbol('X')
expression = X + X + 1
print(expression)

#define multiple symbols
a, b, c = symbols('a, b, c')
expression = a*b + b*a + a*c + c*a
print(expression)
```
#

## Adding Symbols
```
str1="a"
str2="b"

print ("String 1:",str1)
print ("String 2:",str2)

str=str1+str2

print("Concatenated two different strings:",str)
```
```
Simpler:

str1="a"
str2="b"

str=str1+str2

print(str)
```
#

(Task 1) takes a number and squares it. (Task 2) take the square root of the result you get from the task(1)

```
#(task 1)take a number and square it
x = 6
y = x**2
print(y)
#(task 2) take square root of the result you get from task(1)
import math #math library
z = math.sqrt(y) #using sqrt()
print(z)
```

Use a library called math, which is a built-in python library to do quick mathematical operations. The function math.sqrt takes the square root of the result y that we got from (task 1).

#

## Increment a number by 5 times

Take a number eg. 6 and add +1(increment) to it five times

There are two methods to do this,

```
# method number one: 
x = 6
x+=1
x+=1
x+=1
x+=1
x+=1
print(x)
#method number 2
x = 6
x+=5 #increment 5 times
print(x)
```

#

## Converting Celsius to Fahrenhit

The formula to convert celsius to fahrenhit is,

F = 9/5* C +32

```
Celsius = 45
Fahrenheit = 9.0/5.0 * Celsius + 32
print(Fahrenheit)
```
#

## Converting KMPH to MPH

The formula to convert KMPH to MPH is,

MPH = 0.6214 * KMPH

```
kmph = 100
mph =  0.6214 * kmph
print(mph)
```
#

## Pi

```
# Import math Library 
import math 
 
# Print the value of pi 
print (math.pi)
```
#

## Infinity

Infinity basically means something which is never-ending or boundless from both directions i.e. negative and positive. It cannot be depicted by a number. The math.inf constant returns of positive infinity. For negative infinity, use -math.inf.

```
# Import math Library 
import math 
 
# Print the positive infinity 
print (math.inf) 
 
# Print the negative infinity 
print (-math.inf)
```
#

## NAN

The math.nan constant returns a floating-point nan (Not a Number) value. This value is not a legal number. The nan constant is equivalent to float(“nan”).

```
# Import math Library 
import math 
 
# Print the value of nan 
print (math.nan)
```
#


## Ceiling and Floor Value

Ceil value means the smallest integral value greater than the number and the floor value means the greatest integral value smaller than the number. This can be easily calculated using the ceil() and floor() method respectively.

```

# Python code to demonstrate the working of 
# ceil() and floor() 
 
# importing "math" for mathematical operations 
import math 
 
a = 2.3
 
# returning the ceil of 2.3 
print ("The ceil of 2.3 is : ", end="") 
print (math.ceil(a)) 
 
# returning the floor of 2.3 
print ("The floor of 2.3 is : ", end="") 
print (math.floor(a)) 
```
#


## Factorial

Using the factorial() function we can find the factorial of a number in a single line of the code. An error message is displayed if number is not integral.

```
# Python code to demonstrate the working of
# factorial()
 
# importing "math" for mathematical operations
import math
 
a = 5
 
# returning the factorial of 5
print("The factorial of 5 is : ", end="")
print(math.factorial(a))
```
#

## GCD 

gcd() function is used to find the greatest common divisor of two numbers passed as the arguments. 

```

# Python code to demonstrate the working of 
# gcd() 
 
# importing "math" for mathematical operations 
import math 
 
a = 15
b = 5
 
# returning the gcd of 15 and 5 
print ("The gcd of 5 and 15 is : ", end="") 
print (math.gcd(b, a)) 
```
#

## Absolute Value

fabs() function returns the absolute value of the number.

```
# Python code to demonstrate the working of 
# fabs()
 
# importing "math" for mathematical operations 
import math 
 
a = -10
 
# returning the absolute value. 
print ("The absolute value of -10 is : ", end="") 
print (math.fabs(a))
```
#

## Power of exp

exp() method is used to calculate the power of e i.e. e^y         or we can say exponential of y.

```
# Python3 code to demonstrate 
# the working of exp() 
import math 
 
# initializing the value 
test_int = 4
test_neg_int = -3
test_float = 0.00
 
# checking exp() values 
# with different numbers 
print (math.exp(test_int)) 
print (math.exp(test_neg_int)) 
print (math.exp(test_float))
```
#

## Power of a Number

pow() function computes x**y. This function first converts its arguments into float and then computes the power.

```
# Python code to demonstrate pow()
# version 1
 
print ("The value of 3**4 is : ",end="")
 
# Returns 81
print (pow(3,4))
```
#

## Finding the Logarithm

log() function returns the logarithmic value of a with base b. If the base is not mentioned, the computed value is of the natural log.

log2(a) function computes value of log a with base 2. This value is more accurate than the value of the function discussed above.

log10(a) function computes value of log a with base 10. This value is more accurate than the value of the function discussed above.

```
# Python code to demonstrate the working of 
# logarithm
 
# importing "math" for mathematical operations 
import math 
 
 
# returning the log of 2,3 
print ("The value of log 2 with base 3 is : ", end="") 
print (math.log(2,3)) 
 
# returning the log2 of 16 
print ("The value of log2 of 16 is : ", end="") 
print (math.log2(16)) 
    
# returning the log10 of 10000 
print ("The value of log10 of 10000 is : ", end="") 
print (math.log10(10000))
```
#

## Finding the Square Root

sqrt() function returns the square root of the number. 

```
# Python3 program to demonstrate the 
# sqrt() method 

# import the math module 
import math 

# print the square root of 0 
print(math.sqrt(0)) 

# print the square root of 4 
print(math.sqrt(4)) 

# print the square root of 3.5 
print(math.sqrt(3.5))
```
#

## Finding Sine, Cosine, and Tangent

sin(), cos(), and tan() functions returns the sine, cosine, and tangent of value passed as the argument. The value passed in this function should be in radians.

```
# Python code to demonstrate the working of 
# sin(), cos(), and tan() 
 
# importing "math" for mathematical operations 
import math 
 
a = math.pi/6
 
# returning the value of sine of pi/6 
print ("The value of sine of pi/6 is : ", end="") 
print (math.sin(a)) 
 
# returning the value of cosine of pi/6 
print ("The value of cosine of pi/6 is : ", end="") 
print (math.cos(a)) 
 
# returning the value of tangent of pi/6 
print ("The value of tangent of pi/6 is : ", end="") 
print (math.tan(a))
```
#

## Converting Values from Degrees to Radians

degrees() function is used to convert argument value from radians to degrees.
radians() function is used to convert argument value from degrees to radians.

```
# Python code to demonstrate the working of 
# degrees() and radians() 

# importing "math" for mathematical operations 
import math 

a = math.pi/6
b = 30

# returning the converted value from radians to degrees 
print ("The converted value from radians to degrees is : ", end="") 
print (math.degrees(a)) 

# returning the converted value from degrees to radians 
print ("The converted value from degrees to radians is : ", end="") 
print (math.radians(b))
```
#

## Finding Gamma Value

The gamma() function is used to return the gamma value of the argument.

```
# Python code to demonstrate 
# working of gamma() 
import math 

# initializing argument 
gamma_var = 6

# Printing the gamma value. 
print ("The gamma value of the given argument is : "
					+ str(math.gamma(gamma_var))) 
```
#

## Infinity or NaN

isinf() function is used to check whether the value is infinity or not.

```
# Python3 code to demonstrate 
# the working of isnan() 
import math 

# checking isnan() values 
# with inbuilt numbers 
print (math.isinf(math.pi)) 
print (math.isinf(math.e)) 


# checking for NaN value 
print (math.isinf(float('inf')))
```

# isnan() 

This function returns true if the number is “NaN” else returns false.

```

# Python3 code to demonstrate 
# the working of isnan() 
import math 
 
# checking isnan() values 
# with inbuilt numbers 
print (math.isnan(math.pi)) 
print (math.isnan(math.e)) 

 
# checking for NaN value 
print (math.isnan(float('nan')))
```
#

## REFERENCES

[Python math module](https://docs.python.org/3/library/math.html)

[Complex Numbers in Python](https://www.geeksforgeeks.org/complex-numbers-in-python-set-1-introduction/)

[Top 11 Python Libraries for Mathematics and Computation](https://www.pythonstacks.com/blog/post/libraries-mathematics-and-computation/)

[GitHub Search: Python Math](https://github.com/search?q=math+language%3APython&ref=opensearch&type=repositories&l=Python)
