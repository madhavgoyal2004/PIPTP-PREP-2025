## MCQ 1: Simple Print After Recursive Call

**Pseudo-code:**

```
function printUp(n):
    if n == 0:
        return
    printUp(n - 1)
    print(n)

printUp(3)
```

**What will be the output?**
**A)** 3 2 1
**B)** 1 2 3
**C)** 1 2
**D)** 2 3 1

**Approach:**
This is a recursive function where the `print(n)` statement is executed *after* the recursive call. This means the smaller values of `n` will be processed (and their respective recursive calls will complete) before the current `n` is printed. This results in an ascending order of printed values.

**Answer:** **B)** 1 2 3

-----

## MCQ 2: Double Recursive Call with Statements After

**Pseudo-code:**

```
function mystery(n):
    if n == 0:
        return
    mystery(n - 1)
    mystery(n - 1)
    print(n)

mystery(2)
```

**What will be the output ?**
**A)** 1 1 2 1 1 2
**B)** 1 2 2
**C)** 1 1 2
**D)** 1 2 1 2

**Approach:**
This recursive function has two recursive calls before the `print(n)` statement. This means that for a given `n`, `n` will only be printed after both `mystery(n-1)` calls have completed. Due to the double recursion, the base case will be reached multiple times, and the prints will occur as the calls unwind.

**Answer:** **C)** 1 1 2

-----

## MCQ 3: Print After Recursive and Inside a Loop

**Pseudo-code:**

```
function loopRec(n):
    if n == 0:
        return
    for i = 1 to 2:
        loopRec(n - 1)
    print(n)

loopRec(2)
```

**What will be the output?**
**A)** 1 1 2
**B)** 2 1 1
**C)** 1 2 1
**D)** 1 1 1 2

**Approach:**
This recursive function includes a loop that makes recursive calls. The `print(n)` statement is outside the loop but inside the function, meaning `n` is printed only after all loop iterations for that specific `n` have completed their recursive calls.

**Answer:** **A)** 1 1 2

-----

## MCQ 4: Recursive Function with Accumulator Update After Call

**Pseudo-code:**

```
function sumDown(n,total):
    if n == 0:
        print(total)
        return
    sumDown(n - 1,total + n)
    print(n)

sumDown(3, 0)
```

**What is the output?**
**A)** 6 3 2 1
**B)** 0 1 2 3
**C)** 3 2 1 6
**D)** 6

**Approach:**
This function uses recursion with an accumulator (`total`). The `print(total)` statement is in the base case (`n == 0`), so the final accumulated sum will be printed when the recursion bottoms out. The `print(n)` statement is *after* the recursive call, meaning `n` will be printed as the calls unwind.

**Answer:** **A)** 6 3 2 1

-----

## MCQ 5: Reverse Array Print with Recursion

**Pseudo-code:**

```
array = [10, 20, 30, 40]
function reversePrint(i):
    if i == length(array):
        return
    reversePrint(i + 1)
    print(array[i])

reversePrint(0)
```

**What will be the output?**
**A)** 10 20 30 40
**B)** 40 30 20 10
**C)** 30 20 10 40
**D)** 10 30 20 40

**Approach:**
This recursive function traverses the array by incrementing the index `i` in each recursive call. The `print(array[i])` statement is executed *after* the recursive call `reversePrint(i + 1)`. This means that elements will be printed as the recursive calls return, starting from the last element and going backwards.

**Answer:** **B)** 40 30 20 10