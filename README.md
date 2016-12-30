# Code_wars_solutions
"""Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p we want to find a positive integer k, 
if it exists, such as the sum of the digits of n taken to the successive powers of p is equal to k * n."""

'''Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k '''

''' Example:'''
'''46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51'''

'''Solution:'''

def dig_pow(n, p):
    number = str(n)
    total = 0
    for i in number:
        total += pow(int(i), p)
        p += 1
    if total % n == 0:
        return total //n
    else:
        return -1
