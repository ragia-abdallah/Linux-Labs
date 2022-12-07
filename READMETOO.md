# Linux-Labs
Lab 3
1. Using vi write your CV in the file mycv. Your CV should include your name, age, school, college, experience,...

![Lab3-1](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-1%20again.png)

2. Open mycv file using vi command then: Without using arrows state how to:
	a. Move the cursor down one line at time.
		> j
	b. Move the cursor up one line at time.
		> k
	c. Search for word age
		> /age
	d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
		> 5G
	e. Delete the line you are on and line 5.
		> dd
	f. How to step to the end of line and change to writing mode in one-step.
		> A

3. List the available shells in your system.

![Lab3-3](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-3.png)

4. List the environment variables in your current shell.

![Lab3-4](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-4.png)

5. List all of the environment variables for the bash shell.

![Lab3-5](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-5.png)

6. What are the commands that list the value of a specific variable?

![Lab3-6](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-6.png)

7. Display your current shell name.

![Lab3-7](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-7.png)

8. State the initialization files of: sh, ksh, bash.

sh: /etc/profile
ksh: /etc/profile.ksh - ~/profile.ksh
bash: /etc/profile - ~/.bashrc - ~/.bash_profile

9. Edit in your profile to display date at login and change your prompt permanently.

![Lab3-9](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-9.png)

10. Execute the following command :
	echo \ then press enter
	What is the purpose of \ ? 
		>> line break without ending command
	Notice the prompt ”>” what is that? and how can you change it from “>” to “:”. 
		>> ">" is second line prompt stored in PS2, changed by changing the value of the variable

![Lab3-10.3](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-10.3.png)

11. Create a Bash shell alias named ls for the “ls –l” command

![Lab3-11](https://github.com/ragia-abdallah/Linux-Labs/blob/main/Lab3%20Pics/Lab3-11.png)

