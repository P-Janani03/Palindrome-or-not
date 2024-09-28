# Palindrome-or-not
Accept a string and tell me if it is a palindrome or not

word = input('enter a word: ')
if word[0:] == word[::-1]:
    print('It is a palindrome: ' + word)
else:
    print("It's not a palindrome: "+ word)
