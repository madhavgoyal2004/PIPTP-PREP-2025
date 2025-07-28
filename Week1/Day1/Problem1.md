## Problem 1
void fun (Integer w, Integer x)
Integer y
Set y = 0
if(x mod w == 0 || w mod x == 0)
    y = y + 1
else 
    y = y + 10
End if
Print y
End function fun()

# find the answer of fun(40, 4) ? options are [1 , 11 , 10, 2]

## Approach
In this problem, we know mod give the range of 0 to n-1. so we get the one value 0 and another is greater than 0. if 0 comes then number is divisible by n.

## Solution 
40 % 4 == 0
y = 1.
answer => 1