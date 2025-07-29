# Problem 1

## Pseudocode:
```
Integer a, b, c
Set a = 2, b = 6, c = 8
a = (10 + 9) + c
if ((c + b) > (a - c))
    a = b + c
    b = b + b
End if
Print a + b + c
```

**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the execution of the pseudocode by updating the variables a, b, and c sequentially and evaluating the if condition with the current values.

**Answer:** The output is **41**.

---

# Problem 2

## Pseudocode:
```
Integer funn(Integer a, Integer b, Integer c)
b = 7 + a
a = (a + c) + a
b = (b + b) + c
c = 1 + b
return a + b + c
End function funn()
```

**Question:** What will be the output of the following pseudocode for a = 0, b = 2, c = 10?

**Approach:** Trace the function's execution step-by-step, updating a, b, and c as per the order of statements, paying attention to the current values of variables at each step.

**Answer:** The output is **59**.

---

# Problem 3

## Pseudocode:
```
Integer pp, qq, rr
Set pp = 0, qq = 6, rr = 7
pp = rr + pp
pp = (rr & 4) ^ rr
if ((qq & pp & rr) < (rr & qq))
    if ((qq ^ pp) < (rr + qq))
        rr = (3 + 1) ^ pp
    End if
End if
Print pp + qq + rr
```

**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the values of pp, qq, and rr through the sequential operations and nested if conditions, correctly applying bitwise AND (&) and bitwise XOR (^) operators.

**Answer:** The output is **16**.

---

# Problem 4

## Pseudocode:
```
Integer p, q, r
Set p = 9, q = 6, r = 10
if ((q ^ p ^ r) > (r ^ q))
    r = (11 & 12) + q
End if
if ((q ^ 6 ^ 8) > (p ^ 4))
    p = (r + 3) & r
End if
Print p + q + r
```

**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the variables p, q, and r through the if conditions, evaluating the bitwise XOR (^) and AND (&) operations, and skipping blocks if conditions are false.

**Answer:** The output is **25**.

---

# Problem 5

## Pseudocode:
```
Integer pp, qq, rr
Set pp = 1, qq = 2, rr = 8
if ((5 + 8) < (7 + qq))
    if ((qq + pp) < (pp = qq))
        rr = (rr + 6) + rr
    rr = (qq + pp) + pp
End if
rr = rr + pp
Else
    if ((pp + qq - rr) < (rr + pp))
        pp = pp + rr
        rr = (pp & rr) + pp
    End if
End if
Print pp + qq + rr
```

**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the execution flow, evaluating the initial if condition and, if false, proceeding to the else block and its nested if condition, updating variables accordingly.

**Answer:** The output is **28**.

---

# Problem 6

## Pseudocode:
```
Integer p, q, r
Set p = 8, q = 4, r = 5
if ((r + q) < (q - r) || p > q)
    q = (q & 8) & r
End if
Print p + q + r
```

**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the initial variable assignments, then evaluate the if condition which includes relational and logical OR (||) operators, considering operator precedence. If the condition is true, update q using bitwise AND (&).

**Answer:** The output is **13**.

---

# Problem 7

## Pseudocode:
```
Integer funn( Integer a, Integer b, Integer c)
for (each c from 5 to 9)
    if ((b + 5) > (a - b))
        a = (b + 5) ^ a
    End if
    b = 5 ^ c
End for
return a + b
```

**Question:** What will be the output of the following pseudocode for a=1, b=2, c=9?

**Approach:** Trace the loop execution for c from 5 to 9, updating a and b in each iteration based on the if condition and the bitwise XOR (^) operations.

**Answer:** The output is **40**.

# Problem 8
## Pseudocode:

```
Integer funn (Integer a, Integer b, Integer c)
if ((a & 7 & b) > (6 & a))
    b = (12 + 7) + a
    c = (12 + 4) + b
End if
if ((2 + 3) < (5 + b))
    b = (b + 3) + c
    a = (9 & 10) + c
End if
return a + b + c
```
**Question:** What will be the output of the following pseudocode for a = 2, b = 6, c = 5?

**Approach:** Trace the execution by evaluating the two independent if conditions sequentially. Update variables a, b, and c based on the conditions and bitwise AND (&) operations.


**Answer:** The output is 32.

# Problem 9
## Pseudocode:
```
Integer p,q,r
Set p = 0, q = 8, r = 10
if (p < r && (p & q) < r)
    q = 4 & q
    p = (q + 3) ^ r
End if
r = (q & 1) + p
q = (q ^ 9) + p
Print p + q + r
```
**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the execution from initialization through the if condition, evaluating logical AND (&&), bitwise AND (&), and bitwise XOR (^) operators. Then, perform the subsequent assignments and calculate the final sum.


**Answer:** The output is 36.


# Problem 10
## Pseudocode:
```
Integer p, q, r
Set p = 1, q = 4, r = 7
p = (1 + 8) + q
r = (p & r) + r
r = q + q
if ((q + r) < (r - q) && 7 > p)
    p = r + q
    p = (p + 11) + q
End if
Print p + q + r
```
**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the variables p, q, and r through the assignments, bitwise AND (&), and the if condition involving logical AND (&&). Calculate the final sum.


**Answer:** The output is 25.


# Problem 11
## Pseudocode:
```
Integer p, q, r
Set p = 6, q = 3, r = 9
if ((p & r) < (q - p))
    p = (2 ^ 7) + r
    p = (p + 3) ^ r
    q = 4 ^ q
End if
r = (r + p) & q
Print p + q + r
```
**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the variables p, q, and r from initialization. Evaluate the if condition involving bitwise AND (&) and subtraction. If the condition is false, skip the if block and proceed to the final assignment of r and the print statement.


**Answer:** The output is 12.

# Problem 12
## Pseudocode:
```
Integer pp, qq, rr
Set pp = 8, qq = 4, rr = 5
for (each rr from 4 to 5)
    if ((rr - pp + qq) < (qq + rr))
        pp = (5 + 5) + qq
    End if
    pp = (rr + qq) + pp
End for
Print pp + qq
```
**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the loop for rr values from 4 to 5. Inside the loop, evaluate the if condition and perform the updates to pp based on the condition and subsequent line. Finally, print the sum of pp and qq.


**Answer:** The output is 27.

# Problem 13
## Pseudocode:
```
Integer p, q, r
Set p = 4, q = 2, r = 4
for (each r from 5 to 6)
    q = (r + r) + q
    if ((p + r - q) < (6 - p))
        p = p + q
        q = 12 + r
    End if
End for
Print p + q
```
**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the loop for r values from 5 to 6. Inside the loop, update q, evaluate the if condition, and update p and q accordingly. Finally, print the sum of p and q.


**Answer:** The output is 45.


# Problem 14
## Pseudocode:
```
Integer a, b, c
Set a = 1, b = 2, c = 9
if ((b + c) > (c - b))
    c = a + a
End if
if ((7 + 3) < (6 + a))
    b = 12 + a
End if
Print a + b + c
```
**Question:** What will be the output of the following pseudocode?

**Approach:** Trace the execution by initializing a, b, and c, then evaluate each if condition sequentially and update the variables as prescribed. Finally, calculate and print the sum a + b + c.


**Answer:** The output is 5.

# Problem 15
## Pseudocode:
```
Integer funn (Integer a, Integer b, Integer c)
if ((c + a + b) < (b + c))
    if ((c ^ b ^ a) < (b + a + c))
        if ((b + a - c) < (6 - b))
            c = (c & 11) + a
        End if
    End if
End if
a = 1 & c
c = a ^ a
return a + b + c
```
**Question:** What will be the output of the following pseudocode for a = 6, b = 8, c = 4?

**Approach:** Trace the initial values through the nested if conditions. Since the first condition is false, the nested blocks are skipped. Then, perform the final assignments for a and c and return their sum with b.


**Answer:** The output is 8.

# Problem 16
## Pseudocode:
```
Integer funn (Integer a, Integer b, Integer c)
b = c ^ c
c = (12 + 8) + c
if ((b & a) < a && 2 > a)
    b = 4 + b
    b = (9 + 3) + b
Else
    a = 3 ^ c
End if
return a + b + c
```
**Question:** What will be the output of the following pseudocode for a = 3, b = 4, c = 4?

**Approach:** Trace the function's execution by first performing the initial assignments and then evaluating the if condition, which includes bitwise AND (&) and logical AND (&&). Execute either the if or else block based on the condition, and finally return the sum of the updated variables.


**Answer:** The output is 51.

# Problem 17
## Pseudocode:
```
Integer funn (Integer a, Integer b, Integer c)
for (each c from 4 to 5)
    b = c + b
    if ((4 - c - a) < (a + b))
        b = (b + 8) + b
        b = (a ^ b) + b
    Else
        b = (c ^ 0) + c
        Jump out of the loop
    End if
End for
return a + b
```
**Question:** What will be the output of the following pseudocode for a = 1, b = 6, c = 5?

**Approach:** Trace the loop iterations for c from 4 to 5. In each iteration, update b and evaluate the if condition. If the condition is true, perform the nested updates to b involving bitwise XOR (^). If false, update b and exit the loop. Finally, return a + b.


**Answer:** The output is 266.