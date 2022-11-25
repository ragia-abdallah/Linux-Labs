# Linux-Labs
1. Create a user account with the following attribute
> username: islam
> Fullname/comment: Islam Askar
> Password: islam

![Lab2-1](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-1.png)

2.
Create a user account with the following attribute
> Username: baduser
> Full name/comment: Bad User
> Password: baduser

![Lab2-2](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-9.png)

3.
Create a supplementary (Secondary) group called pgroup with group ID of 30000

![Lab2-3](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-3.png)

4.
Create a supplementary group called badgroup

![Lab2-4](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-4.png)

5.
Add islam user to the pgroup group as a supplementary group

![Lab2-5](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-5.png)

6.
Modify the password of islam's account to password

![Lab2-6](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-6.png)

7.
Modify islam's account so the password expires after 30 days

![Lab2-7](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-7.png)

8.
Lock bad user account so he can't log in

![Lab2-8](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-8.png)

9.
Delete bad user account

![Lab2-9](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-9.png)

10. Delete the supplementary group called badgroup.

![Lab2-10](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-10.png)

13. Create a folder called myteam in your home directory and change its permissions to
read only for the owner.

![Lab2-13](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-13.png)

14. Log out and log in by another user
15. Try to access (by cd command) the folder (myteam)

![Lab2-14-15](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-14-15.png)

16. Using the command Line
> Change the permissions of oldpasswd file to give owner read and write
permissions and for group write and execute and execute only for the others
(using chmod in 2 different ways)
![Lab2-16.1](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-16.1.png)
> Change your default permissions to be as above.
![Lab2-16.2](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-16.2.png)
> What is the maximum permission a file can have, by default when it is just
created? And what is that for directory.
![Lab2-16.3](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-16.3.png)
> Change your default permissions to be no permission to everyone then create a
directory and a file to verify.
Made with
by
![Lab2-16.4](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-16.4.png)

17.
What are the minimum permission needed for:
1. Copy a directory:
source directory: read
target parent directory: write & execute
2. Copy a file:
source file: read
target parent directory: write & execute
3. Delete a file:
file: none
parent directory: write & execute
4. Change to a directory: execute
5. List a directory content: read
6. View a file content: read
7. Modify a file content: write (should have read to guarantee integrity and not overwrite content)


18. Create a file with permission 444. Try to edit in it and to remove it? Note what
happened.

![Lab2-18.2](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-18.1.png)
![Lab2-18.2](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab2%20Pics/Lab2-18.2.png)

19. What is the difference between the “x” permission for a file and for a
directory?
x for directory: (granted by default) allows accessing directories
x for file: (devied by default) allows using executable files (commands)
