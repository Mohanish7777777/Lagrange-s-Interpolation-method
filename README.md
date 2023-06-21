# Lagrange-s-Interpolation-method
Using Lagrange interpolation formula, find the value corresponding to 𝒙 = 𝟏𝟎 from the
following table
x 0 1 2 4 5 6
y 1 14 15 5 6 19

Program:
```python3
x= [0,1,2,4,5,6]
y= [1,14,15,5,6,19]
s=float (input ("Enter the value of x to be in: "))
sum=0
for i in range (0,6):
prod=1
 for j in range (0,6):
 if i!=j:
prod=prod*(s-x[j])/(x[i]-x[j])
 sum=sum+prod*y[i]
print ("The functional value is %.4f"%sum)
```
Output:
Enter the value of x to be in: 10
The functional value is 311.0000
