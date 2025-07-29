## Problem 1

**Pseudocode:**

```
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
```

**Question:** find the answer of fun(40, 4) ? options are [1, 11, 10, 2]

**Approach:** Trace the execution of the function with `w = 40` and `x = 4`, evaluating the modulo operations and the `if` condition.

**Answer:** The answer is 1.

## Problem 2

**Pseudocode:**

```
Integer a
Set a = 1
while (a < 5)
    a = a + 2
End while
Print a
```

**Question:** For how many times will the `while` loop be executed? options are [1, 4, 2, 3]

**Approach:** Trace the value of `a` through each iteration of the `while` loop until the condition `a < 5` becomes false.

**Answer:** The `while` loop is executed 2 times.

## Problem 3

**Pseudocode:**

```
def fun(a, b):
    if (a and b and (a + b) > 0):
        return a + fun(a - 2, b - 2) + b
    return a ^ b
res = fun(8, 8)
print(res)
```

**Question:** What will be the output of the following pseudocode for a = 8, b = 8? options are [39, 46, 48, 40]

**Approach:** This is a recursive function. Trace the calls by evaluating the `if` condition and recursive calls, remembering that `^` is bitwise XOR and `and` is logical AND.

**Answer:** The output is 40.

## Problem 4

**Pseudocode:**

```
Integer a, b
Set a = 3, b = 3
if (1 ^ 1)
    a = 1
else
    b = 2
End if
Print a + b
```

**Question:** What will be the output of the following pseudocode? options are [16, 1, 5, 6]

**Approach:** Trace the values of `a` and `b`, evaluate the bitwise XOR `(1 ^ 1)` which determines the `if` or `else` branch, and then calculate `a + b`.

**Answer:** The output is 5.

## Problem 5

**Pseudocode:**

```
Integer funn(Integer a, Integer b)
for (each c from 2 to 4)
    if ((a mod 2) < (b mod 3))
        a = 4 mod 3
    if (5 mod 3 > b)
        a = b
    b = 1
return a + b
End function funn()
```

**Question:** Assuming an initial call of `funn(7, 5)`, what will be the output? options are [23, 2, 6, 8]

**Approach:** Trace the values of `a` and `b` through each iteration of the `for` loop, evaluating the modulo operations and conditional statements.

**Answer:** The output is 2.

## Problem 6

**Pseudocode:**

```
def fun(a, b):
    if (a > 0):
        return fun(a - 2, a + b) + fun(a - 3, a + b) + fun(a - 4, a + b)
    else:
        a = b
        b = a
        return a + b
print(fun(4, 3))
```

**Question:** What will be the output of the following pseudocode for a = 4, b = 3? options are [116, 117, 114, 125]

**Approach:** This is a recursive function. Trace the execution by substituting values for each recursive call and evaluating the base case when `a <= 0`.

**Answer:** The output is 116.

## Problem 7

**Pseudocode:**

```
Integer funn (Integer a, Integer b)
a = a + a
b = b + b
return a + b
End function funn()
```

**Question:** What will be the output of the following pseudocode for a = 6, b = 1? options are [23, 14, 12, 16]

**Approach:** Substitute the initial values of `a` and `b` and perform the arithmetic operations sequentially before returning their sum.

**Answer:** The output is 14.

## Problem 8

**Pseudocode:**

```
Integer a, b, c
Set a = 2, b = 4, c = 2
if (b - a)
    b = a ^ b
    a = c
if (b)
    a = a ^ b
    b = b - 1
if (c)
    a = b
Print a + b + c
```

**Question:** What will be the output of the following pseudocode? options are [13, 12, 30, 9]

**Approach:** Trace the values of `a`, `b`, and `c` through each conditional statement, evaluating the bitwise XOR (`^`) and checking if conditions are non-zero for `TRUE`.

**Answer:** The output is 12.

## Problem 9

**Pseudocode:**

```
Integer a, b, c
Set a = 2, b = 3
for (each c from 4 to 6)
    a = a | b
    if (a > 4)
        a = 0
    if (a + 2)
        b = a + 10
    else
        Jump out of the loop (break)
    b = a + 1
Print a + b
```

**Question:** What will be the output of the following pseudocode? options are [7, 23, 7, 15]

**Approach:** Trace the values of `a` and `b` through the loop, performing bitwise OR (`|`) and conditional assignments, noting that `if(x)` executes if `x` is non-zero. The provided Python solution in the source material uses `a=a+b` instead of `a=a|b`, leading to the stated answer.

**Answer:** The output is 7.

## Problem 10

**Pseudocode:**

```
Integer m, n
Set m = 9, n = 6
m = m + 1
n = n - 1
m = m + n
if (m > n)
    print m
else
    print n
End if
```

**Question:** What will be the output of the following pseudocode? options are [5, 10, 15, 6]

**Approach:** Trace the step-by-step modification of variables `m` and `n`, then evaluate the `if` condition to determine which value is printed.

**Answer:** The output is 15.

## Problem 11

**Pseudocode:**

```
Integer p, q, r
Set p = 1, q = 4, r = 2
if ((p ^ q) > (p & q))
    r = p & q
else
    r = p ^ q
End if
if (q > r && r > p)
    p = q
End if
Print p - q + r - 2
```

**Question:** What will be the output of the following pseudocode? options are [5, 0, 12, 3]

**Approach:** Trace the values of `p`, `q`, and `r` through the conditional statements, evaluating bitwise XOR (`^`), bitwise AND (`&`), and logical AND (`&&`).

**Answer:** The output is -5.