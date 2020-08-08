# SCAMP-Assessment
Using Python
#Program to display the Fibonacci Sequence up to the n-th term
nterms = int(input ("How many terms? "))
#first two terms
n1, n2 = 0,1
count = 0
#check if the number of the terms are valid
if nterms <=0:
    print (" Please enter a positive integer ")
elif nterms==1:
     print ("Fibonacci Sequence up to",nterms,":")
     print (n1)
 else:
     print ("Fibonacci Sequence:")
while count< nterms:
     print (n1)
     nth = n1+n2
#update values
     n1 = n2
     n2 = nth
count += 1
 
