# CSCI160-CH06-LAB
Programming Exercises From Java Illuminated Book by Anderson and Franceschi  
## 06_64 Instructions  
Write a program that takes an integer value as an input and converts that value to its binary representation;  for instance, if the user inputs 17, then the output will be 10001.  
### Q06_64 Test 1
**Input:**  
17  
**Output:**  
The binary equivalent of 17 is 10001  
### Q06_64 Test 2
**Input:**  
216    
**Output:**  
The binary equivalent of 216 is 11011000  
## 06_66 Instructions  
Write a program that simulates an XOR operation.  The input should be a word representing a binary number (0's and 1's). Your program should XOR all the digits from left to right and output the results as "True" or "False".  In an XOR operation, *a XOR b* is true if a or b is true but not both; otherwise, it is *false*.  
In this program, we will consider the character "1" to represent true and a "0" to represent false.  For instance, if the input is 1011, then the output will be 1 (1 XOR 0 is 1, then 1 XOR 1 is 0, then 0 XOR 1 is 1, which causes the output to be "True").  You can assume the input word is guaranted to contain only 0's and 1's.  
### Q06_66 Test 1
**Input:**  
1011     
**Output:**  
The result is true  
### Q06_66 Test 2
**Input:**  
10111     
**Output:**  
The result is false  
## Q66_67 Instructions  
Write a program that takes a word as an input and checks whether that sentence is a palindrome.  A palindrome is a word, phrase or sentence that is symmetrical;  that is, it is spelled the same forward and backward.  Examples are "otto" and "mom".  Your program should be case insensitive; that is, "Otto" should also be counted as a palindrome.  
### Q06_67 Test 1
**Input:**  
palindrome  
**Output:**  
palindrome is not a palindrome  
### Q06_67 Test 2  
**Input:**  
tacocat     
**Output:**  
tacocat is a palindrome  
### Q06_67 Test 3  
**Input:**  
RaCecAr   
**Output:**  
RaCecAr is a palindrome