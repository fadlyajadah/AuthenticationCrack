# AuthenticationCrack

The file password.txt contains a hashed password for a user that you need to access their account. 

Here's what you know: 
1. The password is encrypted using SHA512 (but you're totally smart enough that you could have figured that out based on how long the hashed output was)
2. You're unsure on the password requirements. There could be numbers, uppercase, lowercase...or not. 
3. You  have been provided a dictionary of the 100 most common passwords.

Choose one of the following three methods: 
1. Brute Force
    john Password
    john Password --show
2. Dictionary Attack
    john Password --wordlist=dictionary.txt
    john Password --show
3. Rainbow Tables

Which will be most effective and why? 
