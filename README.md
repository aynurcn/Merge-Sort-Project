# Merge-Sort-Project
Merge Short Project
# First Part => Stages
---
Input => [16, 21, 11, 8, 12, 22]

| First Half | Second Half |
| :--- | ---: |
| [16, 21, 11] | [8, 12, 22] |
| [16], [21, 11] | [8, 12], [22] |
| [16], [21], [11] | [8], [12], [22] |
| [16], [11, 21] | [8, 12], [22] |
| [11, 16, 21] | [8, 12, 22] |

Output => [8, 11, 12, 16, 21, 22]
# Second Part => Big O Notation
---
- n element => O(n)
- Because it's divided by 2 => 2^x = n => log(n) = x => O(log(n))
- O(n), O(log(n)) => O(nlogn)
