# Cyberoam-Brute

A python script to carry out brute force attack on JIIT cyberoam portal.

#IMP: 
This is useless for anyone looking for easy to run bugfree script.

#Types of attack:
1. Dictionary attack
    Use script post2.py to carry out dictionary attack.You might need to make some changes to supply a list of passwords.
2. Brute Force
    Script checks all the possible combinations for a partcular usename and stores the correct password when found.
#Ideal way to use:
  1. Run python post.py bruteforce in terminal/Powershell
  2. Use the correct passwords from step 1 in post2.py
    
Note: It was written specifically for jiit so passwords combinations checked are of type "aabbcc".

#Finding Usernames
    You can create username file manually or by mounting the smb server in terminal and running ls command on it.
    Details can be found here 
    http://askubuntu.com/questions/29535/how-do-i-access-a-mounted-windows-share-from-the-command-line   

#Future work:
  1. Link both the scripts such that the output from post.py is passed to post2.py and all the usernames for which password was found are eliminated from username.txt
  2. Remove all the useless code from post.py and post2.py