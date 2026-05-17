# Identify the number of vowels in given username.

username = input("Enter username: ")
count = 0
for char in username.lower():
    if char in "aeiou":
        count += 1
print("Number of vowels:", count)