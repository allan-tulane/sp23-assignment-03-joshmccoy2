# CMPS 2200 Assignment 3
## Answers

**Name:**Josh McCoy 


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**

W(n) = W(n-1) + 1
in O(n)
S(n) = S(n-1) + 1
in O(n)

- **d.**
W(n) = 2W(n/2) + 2
S(n) = S(n/2) + 1
scan has W(n) in O(n) and S(n) in O(log n)
reduce has W(n) in O(n) and S(n) in O(log n)


- **f.**

W(n) = 2W(n/2) + n
in O(n*logn)
S(n) = S(n/2) + 1
in o(logn)