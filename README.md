# VernamCipher

Vernam Cipher is a method of encrypting alphabetic text. It is one of the Substitution techniques for converting plain text into cipher text. In this mechanism we assign a number to each character of the Plain-Text, like (a = 0, b = 1, c = 2, … z = 25). 

Method to take key: In the Vernam cipher algorithm, we take a key to encrypt the plain text whose length should be equal to the length of the plain text. 

Encryption Algorithm: 

Assign a number to each character of the plain-text and the key according to alphabetical order. 
Bitwise XOR both the number (Corresponding plain-text character number and Key character number). 
Subtract the number from 26 if the resulting number is greater than or equal to 26, if it isn’t then leave it.

The realisation of the programm:

![image](https://user-images.githubusercontent.com/79413366/210243025-bcba6eef-2a83-4ff4-9c9b-4f8078f91a1c.png)

