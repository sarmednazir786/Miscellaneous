## Title: Twist of Permissions
## Details:
* difficulty: Easy
* category: Miscellaneous 
* author: Sarmed
* flags: flag{permissions have been broken}

## Description:
Permissions are used to limit various users and groups on a machine and give them only required access of the files and folders.  
## Hint:
Sometimes it's right in front of the eyes but you can't see it.

## Intended Learning and outcome:

With this challenge, I was able to learn the importance of permissions and how to change them with respect to other users.

## Solution: 

We are given a zip file that contain a dist folder and a flag executable file inside it. When we attempt to extract the file, we are asked for a password. We proceed to search most common passwords in 2024 and start to try them. We are successful with "123456" password which is on top of the list we find. Then we try to execute the flag executable but it doesn't allow us, we the change permissions with "chmod +x flag" command to provide execution rights and then when we execute it, we get the flag.
