Write a Python program that can take a positive integer greater than 2 as
input and write out the number of times one must repeatedly divide this
number by 2 before getting a value less than 2

num = int(input())
count = 0
if num < 2:
    print("Error")
else:
    while num >= 2:
        num /= 2
        count += 1
    print(count)
        
