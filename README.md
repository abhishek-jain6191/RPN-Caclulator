# RPN Caclulator
"""
A simple stack based approcah has been used to solve the given probelm.
We remove the immediate two elements to the absolute left the operator we encounter and
use the operator on these two operations.

Time Complexity:O(n) for a RPN expression of length n

Memory Complexity:O(n+d) for a RPN expression of length n and d opperators

Please enter the RPN string with a ',' separator. It handels addition, subtraction,
multiplication, division and power operators.


To run the file, open cmd in the location of your file and type in "python3 RPN.py".

It will keep on running till you type in quit.

Submitted by:

Abhishek Jain
abhishekjain.nitc@gmail.com

"""
