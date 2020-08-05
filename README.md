# SCAMP-Accesment
# Fibonacci sequence of a given number.
def find_fibonacci(num);
    # initializing 0th and 1st term
    x, y = 0, 1
    # interating for a given time (num)
    for i in range(num):
        x, y = y, x+y   # swap, & reassign
        return x
