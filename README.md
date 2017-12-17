# python-practice
practice python interview questions
1.  find_index_list.py: Find the index of an item given a list containing it in Python.

2. fuzzbuzz.py: Write a Python program to print numbers from 1 to 100 except for multiples of 3 for which you should print "fuzz" instead, for multiples of 5 you #should print 'buzz' instead and for multiples of both 3 and 5, you should print 'fuzzbuzz' instead.

3. How do you detect whether or not a word is a palindrome?"Write me a function that tells me whether this word is a palindrome.
POP would be a simple palindrome. Poop would also be a palindrome. You need to deal with even and odd numbers. But you also need to  deal with whether the word race car is a palindrome if it has a space in it.

4. #How will you find whether any permutation of a word would be a Palindrome
#test cases to test all possible input
#complexity of the function big O
#logic using Brute force approach with O(mx2^m) time complexity, where m is the size of the word. He told me to optimize it. 
#We will keep track of the counts of each character in the word. If the length of the word is even and if all characters appears even number of times, a palindrome can be formed.
#Similarly, if the length of the string is odd and all characters but one appear even number of times then Palindrome can be formed.
#Else in all other cases Palindrome wont exist in the word. He seemed to be satisfied with my approach and told me to write the full code.


5. #Given a string s consists of upper/lower-case alphabets and empty space characters ' ', return the length of last word in the string.
#If the last word does not exist, return 0.
#Note: A word is defined as a character sequence consists of non-space characters only.
#Example:
#Given s = "Hello World",
#return 5 as length("World") = 5.
#Please make sure you try to solve this problem without using library functions. Make sure you only traverse the string once.




