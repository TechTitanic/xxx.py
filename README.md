# xxx.py
This is the program to check if a list contains a palindrome of elements

list1= [1,2,1]
list2= [1,2,3,4]

copy__list1= list1.copy()
copy__list1.reverse()

if(copy__list1 == list1):
    print("it is palindrome")
else:
    print("it is not palindrome")

