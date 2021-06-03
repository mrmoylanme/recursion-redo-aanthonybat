Complete at least 4 of the recusive functions in main.py

We have triangle made of blocks. The topmost row has 1 block, the next row down has 2 blocks, the next row has 3 blocks, and so on. 

```
[]
[][]
[][][]
```

Compute recursively (no loops or multiplication) the total number of blocks in such a triangle with the given number of rows.

Ex:
```
 traingle(0) → 0
 triangle(1) → 1
 triangle(2) → 3
 triangle(3) → 6
```

```
def triangle(n):
  
```

Radiation decay.  There is a radioactive substance that gives off radiation at a high rate.  Radition is measured by Rads.  Each year the radation it gives off is reduced by 75 percesnt.  For example with a starting value of 10 rads, it would be 2.5 rads after 1 year, and it would be .625 rads after 2 years. It is considered safe if it has less than or equal to .1 Rads.  Given a starting radiation level in rads calculate the number or years till it is below a safe level. Write this recursively no loops or sigle equations. 

Ex:
```
 yearsTillSafe(.1) → 0
 yearsTillSafe(1) → 2
 yearsTillSafe(10) → 4
 yearsTillSafe(50) → 5
```
```
def yearsTillSafe(rads):
  
```

Given an array of ints, compute recursively if the array contains a 6. We'll use the convention of considering only the part of the array that begins at the given index. In this way, a recursive call can pass index+1 to move down the array. The initial call will pass in index as 0.

ex:
```
array6([1, 6, 4], 0) → true
array6([1, 4], 0) → false
array6([6], 0) → true
```

```
def array6(arr, index):
  
```

Reverse List.  Given a string in python return the string reversed.  tips: in python you can get a single character at postion i from string by using myString[i], you can get a substring by saying myString[start:end] using any numbers for start and end.  

Ex:
```
reverse("cat") → "tac"
reverse("aabb") → "bbaa"
reverse("a") → "a"
reverse("") → ""
```
```
def reverse(text):
  
```

Given a non-negative int n, return the product of its digits recursively (no loops). Note that mod (%) by 10 yields the rightmost digit (126 % 10 is 6), while divide (//) by 10 removes the rightmost digit (126 // 10 is 12).

Ex:
```
prodDigits(126) → 12
prodDigits(49) → 36
prodDigits(12) → 2
```
```
def prodDigits(n):
  
```

Given a non-negative int n, return the number of even digits, so for example if n is 212  yields 2. (no loops). Note that mod (%) by 10 yields the rightmost digit (126 % 10 is 6), while divide (//) by 10 removes the rightmost digit (126 // 10 is 12).

Ex: 
```
countEvens(717) → 0
countEvens(2) → 1
countEvens(212) → 2
countEvens(21458) → 3
```
```
def countEvens(n,x):
  
```