**Homework 1:** due Monday, Sep. 16th, 6pm

•	What is the difference between commands ``` wc `grep -l int *` ``` and ```grep -l int * | wc ```? How does the output differ (1pt)? 	


•	Read the man pages about the ```ls``` and ```wc``` commands. Devise a minimal pipeline command that will print the number of files and subdirectories in the current directory (including hidden ones, but not the current and parent directory entries). (1pt)

•	Create a directory called ```IveGotRights``` in your home directory. Set its permissions to: 
read, write, and execute permission for the owner, read and execute permission for the group, execute permission for others. What are the commands to do these tasks? 	
(1pt)

•	Devise a pipeline command using ```head, tail``` and ```grep``` that will extract lines containing Computer Science course codes as distinct words from the 5th to 12th lines: 
```
1.)	This is CSC322 
2.)	CSCABC and some TV tunes 
3.)	All CSC students do MTH309 as part of their major 
4.)	Csc322 is how Dr Rosenberg writes the code 
5.)	CSC322 rules! 
6.)	CSCABC 
7.)	We all have taught Csc517 at some time 
8.)	CSC111MTH111BBC111 
9.)	MTH112 = Calculus II 
10.)	MTH309 is prerequisite to CSC527, and that's a good thing 
11.)	CSC is our code, 911 is the police 
12.)	Artificial Intelligence (CSC545) is not for wimps  
13.)	CSC531 will run next semester 
14.)	ART101 is fun
```
  
The "CSC" must start with an uppercase "C" but the "SC" may be written in any combination of uppercase and lowercase. A correct solution extracts lines numbered 5, 7, 10, and 12. (1pt)

•	Assume you have 3 files named ```file[1,2,3].txt``` that contain 5 columns of data. What would be the command(s) to (i) pool these files, (ii) extract columns 1,2, and 5, (iii) rearrange columns as 5,2 and 1 and (iv) put the information in a file named ```myFile.txt```? (1pt)	
 
