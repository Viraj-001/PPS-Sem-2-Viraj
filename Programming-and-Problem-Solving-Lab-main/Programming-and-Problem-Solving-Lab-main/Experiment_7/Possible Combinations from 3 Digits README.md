## Problem Statement
Write a Python program to accept three digits and print all possible 3-digit combinations that can be formed using those three digits. Each digit should be used exactly once in each combination.
---

## Algorithm
1.Start

2.Input three values a, b, c

3.Store them in a list: digits = [a, b, c]

4.For i from 0 to 2:
For j from 0 to 2:
For k from 0 to 2:
If i ≠ j AND i ≠ k AND j ≠ k:
Print digits[i] + digits[j] + digits[k]

5.Stop

---

## Flowchart
<img width="1024" height="904" alt="image" src="https://github.com/user-attachments/assets/6090cbe0-a6b0-4e7a-86ba-50a1909bd3ca" />






---

## Execution
<img width="1919" height="950" alt="image" src="https://github.com/user-attachments/assets/4c394117-2481-4085-98a7-f5ff6abc1916" />






