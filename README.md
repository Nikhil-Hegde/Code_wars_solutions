# Code_wars_solutions

This respository container contains solutions(Python) to some of the problems given in https://www.codewars.com

Code 1: Given two arrays a and b write a function comp(a, b) (compSame(a, b) in Clojure) that checks whether the two arrays have the 
"same" elements, with the same multiplicities. "Same" means, here, that the elements in b are the elements in a squared, 
regardless of the order.

Code 2: You are going to be given an array of integers. 
Your job is to take that array and find an index N where the sum of the integers to the left of N is equal to the 
sum of the integers to the right of N. If there is no index that would make this happen, return -1

Code 3: Your goal in this kata is to implement an difference function, which subtracts one list from another.
It should remove all values from list a, which are present in list b.

Code 4: Given a positive integer n written as abcd... (a, b, c, d... being digits) and 
a positive integer p we want to find a positive integer k, 
if it exists, such as the sum of the digits of n taken to the successive powers of p is equal to k * n

Code 5: Create a function that takes an integer as an argument and returns "Even" for even numbers or "Odd" for odd numbers.

Code 6: Your task is to construct a building which will be a pile of n cubes. 
The cube at the bottom will have a volume of n^3, the cube above will have volume of (n-1)^3 and so on until the top which will have a volume of 1^3."""
The parameter of the function findNb (find_nb, find-nb) will be an integer m and you have to return the integer n such as n^3 + (n-1)^3 + ... + 1^3 = m if such a n exists or -1 if there is no such n."""

Code 7: An isogram is a word that has no repeating letters, consecutive or non-consecutive. 
Implement a function that determines whether a string that contains only letters is an isogram. 
Assume the empty string is an isogram.

Code 8: Sum all the numbers of the array except the highest and the lowest element (the value, not the index!).
(The highest/lowest element is respectively only one element at each edge, even if there are more than one with the same value!)

Code 9: In this kata you will create a function that takes a list of non-negative integers and strings and 
returns a new list with the strings filtered out

Code 10: Tortoise racing

Code 11: Convert number to reversed array of digits

Code 12: Write a program that finds the summation of every number between 1 and num. 
The number will always be a positive integer greater than 0

Code 13: Given two integers, which can be positive and negative, find the sum of all the numbers between including them too and 
return it. If both numbers are equal return a or b.

Code 14: Check to see if a string has the same amount of 'x's and 'o's. 
The method must return a boolean and be case insensitive. The string can contains any character

Code 15: This program tests the life of an evaporator containing a gas.
We know the content of the evaporator (content in ml), the percentage of foam or gas lost every day (evap_per_day) and 
the threshold (threshold) in percentage beyond which the evaporator is no longer useful. All numbers are strictly positive.
The program reports the nth day (as an integer) on which the evaporator will be out of use.

Code 16: The input is a string str of digits. Cut the string into chunks of size sz (ignore the last chunk if its size is less than sz).
If a chunk represents an integer such as the sum of the cubes of its digits is divisible by 2, reverse it; 
otherwise rotate it to the left by one position. Put together these modified chunks and return the result as a string

Code 17: Gap in Prime

Code 18: A string is considered to be in title case if each word in the string is either 
(a) capitalised (that is, only the first letter of the word is in upper case) or 
(b) considered to be an exception and put entirely into lower case unless it is the first word, which is always capitalised.
Write a function that will convert a string into title case, given an optional list of exceptions (minor words). 
The list of minor words will be given as a string with each word separated by a space. 
Your function should ignore the case of the minor words string -- it should behave in the same way even if the case of the minor word 
string is changed.

Code 19: This kata is to practice simple string output. Jamie is a programmer, and James' girlfriend. 
She likes diamonds, and wants a diamond string from James. Since James doesn't know how to make this happen, he needs your help.
You need to return a string that displays a diamond shape on the screen using asterisk ("*") characters. 
Please see provided test cases for exact output format.
The shape that will be returned from print method resembles a diamond, where the number provided as input represents the number of *’s printed on the middle line. 
The line above and below will be centered and will have 2 less *’s than the middle line. This reduction by 2 *’s for each line continues until a line with a single * is printed at the top and bottom of the figure.
Return null if input is even number or negative (as it is not possible to print diamond with even number or negative number)


