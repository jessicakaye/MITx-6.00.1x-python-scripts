# PROBLEM 3
# 
# Assume s is a string of lower case characters.
# 
# Write a program that prints the longest substring of s in which the letters occur in alphabetical order. In the case of ties, print the first substring.
#

current = s[0]
longest = s[0]

for x in s[1:]:
    if x >= current[-1]:
        current += x
        if len(current) > len(longest):
            longest = current
    else:
        current = x
print("Longest substring in alphabetical order is: ", longest)
