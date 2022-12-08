# prime-number-or-composite-number
By using python we can find the numbers in a range whether it is prime or composite number


Def about():

"enter a positive integer range [A, B] and the system will find out the status (Prime or composite) of each number available

in the given range. At the end print the count also."" lower_value=int(input("Enter the lowest range value: ")) # lowest value

upper_value=int(input("Enter the upper range value: ")) # upper value

a=lower_value

b=upper_value

primeCount=0 #count variable for prime #count variable for composite

compositeCount=0

print ("Prime numbers from {} to {} are:- ".format(a,b)) # prime numbers from lower to upper value

prime="" # append the prime numbers to the string

for n in range (a, b+1): if n>1:

for in range (2, n+1): if n%==0: # prime numbers condition

break

if i==n:

prime+= str(n)

print("Composite numbers from {} to {} are:- ".format(a,b)) #composite numbers

from lower to upper

composite="" # append the composite numbers to the string

for n in range(a,b+1):

if n>1: for i in range(2,n+1): # composite numbers condition

if n%==0: break

if il=n: composite+= str(n)

for i in range(a,b+1):

if str(i) in prime: #to check number in prime numbers string print(" is a prime number".format(int(i))) continue

if str(i) in composite: # to check number in composite numbers string print("{} is a composite number".format(int(i)))
