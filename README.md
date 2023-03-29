# Python program to find number of words in a sentence

my_str = input("Enter a string : ")


# display the original string
print("The original string is : ", my_str)

#find the length of split words
words= len(my_str.split())
print("The number of words in given string are : ",words)
