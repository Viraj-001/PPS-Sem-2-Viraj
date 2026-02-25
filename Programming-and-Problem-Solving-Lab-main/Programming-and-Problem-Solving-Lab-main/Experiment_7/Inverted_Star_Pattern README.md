## Problem Statement
Write a Python program to print an inverted right-angled triangle star pattern.
---

## Algorithm
1.Start
2.Input an integer n
3.Check if n > 0
4.If yes:
Print n stars ("*" * n)
Decrease n by 1 (n = n - 1)
Go back to Step 3
5.If no:
6.Stop
---

## Flowchart
            ┌──────────────┐
            │    START     │
            └──────┬───────┘
                   │
                   ▼
            ┌──────────────┐
            │   INPUT n    │
            └──────┬───────┘
                   │
                   ▼
               ◇────────◇
               │  n > 0? │
               ◇────┬────◇
                    │Yes
                    ▼
            ┌──────────────┐
            │ PRINT "*" * n│
            └──────┬───────┘
                   │
                   ▼
            ┌──────────────┐
            │   n = n - 1  │
            └──────┬───────┘
                   │
                   └───────────────┐
                                   │
                                   ▼
                                (Back to
                                 n > 0?)
                    
                    No
                    │
                    ▼
            ┌──────────────┐
            │     STOP     │
            └──────────────┘


---

## Execution
<img width="1919" height="947" alt="image" src="https://github.com/user-attachments/assets/d71d78fc-3f5e-4326-8073-03ec22fa5ab0" />




