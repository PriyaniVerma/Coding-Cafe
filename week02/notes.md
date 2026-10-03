1. What did 'pwd' print?
/Users/apple

2. What did 'ls -a' show that plain 'ls' did not?
Ls -a showed hidden files and folders that plain ls did not show. There were names starting with .

3. Pick one Line from 'ls-l'. What do you think the first column mean?
The first column shows the file type and permissions. For example, d means it is a directory, while - means it is a regular file. 

4. Why does that work from where you are standing? Which kind of path is 'coding-cafe/week-2'? Absolute or Relative?
It works because coding-cafe/week02 describes the location starting from my current directory, which is may home folder. It is a relative path, not an absolute path. 

5. 'Mv' did two different jobs above. What were they?
First mv moved a file from one directory to another. Second, it renamed a file within the same directory. 

6. How many folders are on your 'PATH'? 


7. Write down exactly where your python3 lives. 
/usr/local/bin/python3

8. Compare your answer to 7 with the person next to you?
He uses windows, I use Mac. It is also different because different computers can have Python installed in different locations. 

9. What exactly did the shell say? Explain the error in your own words, using the word PATH?
The shell searched the folders listed in my PATH for a program called pyton3, but it could not find one. Since pyton3 was also a typo, there was no matching command to run. 

10. '.venv. did not appear with plain 'ls'. Why not?
.venv did not appear with plain ls because its name begins with a dot, so it is a hidden directory. Ls -a shows hidden files and directories. 

11. What changed about your prompt?
.venv appeared at the beginning of my prompt. This shows that the virtual environment is currently activated. 

12. Compare with what you wrote for q7. Is it the same path? If not, what does that tell?
It is different. Activating the virtual environment changed my PATH so that the .venv/bin directory comes earlier, causing the shell to find the virtual environment's Python first. 

13. What is in the second list that was not in the first?
The second list contains requests, which was not in the first line. It also installed dependancies required by requests, such as urllib3, certifi, charset-normaliser, and idna. 

14. Where does 'python3' point now?
/usr/local/bin/python3

15. Find what 'ls-h' does. Write it I your own words. 
Ls-h displays file sizes in a human-readable format, such as KB, MB, or GB, instead of only showing the size as a number of bytes. 

16. What is the different between what Ctrl +C and Ctrl+D did? 
Ctrl+ C interrupts the current process, while Ctrl+D sends an end-of-file signal. In this case, Ctrl+C interrupted Python and Ctrl +D then told the interpreter there was no more input, allowing it to exit. 
