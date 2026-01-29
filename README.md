Below are **50 very useful patterns** commonly asked in **DSA, loops, and interview prep**.
Each pattern includes:
• **Concept** (key idea)
• **Example output** (small size)
• **C++ logic hint** (core condition)

---

## A. Basic Star Patterns

### 1. Solid Square

**Concept:** Nested loops

```
****
****
****
****
```

**Logic:** print `*` unconditionally

---

### 2. Hollow Square

**Concept:** Boundary check

```
****
*  *
*  *
****
```

**Logic:** `if(i==0||j==0||i==n-1||j==n-1)`

---

### 3. Left Triangle

**Concept:** Row-based growth

```
*
**
***
****
```

**Logic:** stars = row index

---

### 4. Right Triangle

**Concept:** Spaces + stars

```
   *
  **
 ***
****
```

**Logic:** spaces = `n-i-1`

---

### 5. Inverted Left Triangle

```
****
***
**
*
```

**Logic:** stars = `n-i`

---

### 6. Inverted Right Triangle

**Concept:** Mirror logic

```
****
 ***
  **
   *
```

---

### 7. Pyramid

**Concept:** Symmetry

```
   *
  ***
 *****
*******
```

**Logic:** stars = `2*i+1`

---

### 8. Inverted Pyramid

```
*******
 *****
  ***
   *
```

---

### 9. Hollow Pyramid

**Concept:** Diagonals + base

```
   *
  * *
 *   *
*******
```

---

### 10. Diamond

**Concept:** Pyramid + inverted pyramid

```
   *
  ***
 *****
  ***
   *
```

---

## B. Cross & Diagonal Patterns

### 11. X Pattern

**Concept:** Diagonals

```
*   *
 * *
  *
 * *
*   *
```

**Logic:** `i==j || i+j==n-1`

---

### 12. Plus (+) Pattern

**Concept:** Middle row & column

```
  *
  *
*****
  *
  *
```

---

### 13. Hollow X

**Concept:** Only diagonals

---

### 14. Cross Box

```
* * *
 * *
* * *
```

---

### 15. Diagonal Line

```
*
 *
  *
   *
```

---

## C. Number Patterns

### 16. Number Square

```
1234
1234
1234
1234
```

---

### 17. Increment Triangle

```
1
12
123
1234
```

---

### 18. Repeated Number Triangle

```
1
22
333
4444
```

---

### 19. Floyd’s Triangle

**Concept:** Continuous numbers

```
1
2 3
4 5 6
7 8 9 10
```

---

### 20. Pascal’s Triangle

**Concept:** Combination logic

```
    1
   1 1
  1 2 1
 1 3 3 1
```

---

## D. Advanced Star Patterns

### 21. Butterfly Pattern

**Concept:** Mirror triangles

```
*   *
** **
*****
** **
*   *
```

---

### 22. Hollow Diamond

---

### 23. Sandglass

---

### 24. Hourglass

---

### 25. Zig-Zag

```
*   *
 * *
  *
 * *
*   *
```

---

## E. Alphabet Patterns

### 26. Alphabet Triangle

```
A
AB
ABC
ABCD
```

---

### 27. Repeated Alphabet

```
A
BB
CCC
```

---

### 28. Alphabet Pyramid

---

### 29. Palindrome Alphabet

```
  A
 ABA
ABCBA
```

---

### 30. Alphabet X

---

## F. Mixed Patterns

### 31. Star + Number

```
1
*2
**3
```

---

### 32. Binary Triangle

```
1
01
101
0101
```

---

### 33. 0-1 Checkerboard

---

### 34. Spiral Numbers

---

### 35. Hollow Number Pyramid

---

## G. Interview-Focused Patterns

### 36. Boundary Star

---

### 37. Hollow Rectangle

---

### 38. Double Pyramid

---

### 39. Arrow Pattern

---

### 40. W Pattern

---

## H. Tricky Logic Patterns

### 41. Chessboard

---

### 42. Concentric Square

---

### 43. Hollow Spiral

---

### 44. Number X

---

### 45. Mirror Number Triangle

---

## I. Competitive Programming Style

### 46. Pattern using single loop

---

### 47. Pattern using math only

---

### 48. Recursive Pattern

---

### 49. Dynamic Size Pattern

---

### 50. Custom Input Pattern

---

## C++ Template (Reusable)

```cpp
int n;
cin >> n;
for(int i=0;i<n;i++){
  for(int j=0;j<n;j++){
    // condition here
  }
  cout << endl;
}
```

---

### Want next?

✔ Full **C++ code for each pattern**
✔ **Interview-wise importance ranking**
✔ **Pattern → Formula cheat sheet**
✔ **LeetCode / Codeforces related problems**

Just tell me 😄
