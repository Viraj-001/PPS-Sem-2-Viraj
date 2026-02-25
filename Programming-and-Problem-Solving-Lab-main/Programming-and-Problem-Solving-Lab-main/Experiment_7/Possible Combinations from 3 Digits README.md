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
                   ┌──────────────┐
            │    START     │
            └──────┬───────┘
                   │
                   ▼
        ┌────────────────────┐
        │  INPUT a, b, c     │
        └─────────┬──────────┘
                  │
                  ▼
        ┌────────────────────┐
        │ digits = [a,b,c]   │
        └─────────┬──────────┘
                  │
                  ▼
        ┌────────────────────┐
        │  i = 0 to 2        │
        └─────────┬──────────┘
                  ▼
        ┌────────────────────┐
        │  j = 0 to 2        │
        └─────────┬──────────┘
                  ▼
        ┌────────────────────┐
        │  k = 0 to 2        │
        └─────────┬──────────┘
                  ▼
            ◇────────────────◇
            │ i≠j AND i≠k AND│
            │     j≠k ?      │
            ◇───────┬────────◇
                    │Yes
                    ▼
        ┌────────────────────┐
        │ Print digits[i] +  │
        │ digits[j] + digits[k]│
        └─────────┬──────────┘
                  │
                  └──────(Loop back)
                    
                    No
                    │
                    ▼
            ┌──────────────┐
            │     STOP     │
            └──────────────┘


---

## Execution
<img width="1919" height="950" alt="image" src="https://github.com/user-attachments/assets/4c394117-2481-4085-98a7-f5ff6abc1916" />






