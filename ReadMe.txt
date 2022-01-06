#############################################################
Practical section number: P6
Asignment question attempted: Q4 (text editor)
#############################################################
1. 2019B1PS0750P: Sudhanshu Mishra
#############################################################
Description of how to run the code and observe the output:

0. If vewing the code in Text Editor on Ubuntu, please set the Tab Width=4, otherwise the indentation looks messy in some places.
1. An executable file is NOT included with this. Compile 2019B4PS0639P_P6.c using the standard gcc and run a.out.(I used gcc version (Ubuntu 9.3.0-10ubuntu2) 9.3.0.)

2. If for some reason, the program doesn't work(due to incompatibility reasons) please use this online compiler: https://www.onlinegdb.com/online_c_compiler
I have checked and the code runs here properly.

3. When you run the executable, it will prompt you to enter a number from 1 to 8 which corresponds to a choice.

4. If something else is entered, an error message is displayed and you are promted for a choice again.

5. Choice 1 will create a new file and write in it.It will prompt you for file name, number of lines and content of lines. If a non-empty file with the same name already exists, an error message is displayed and new file is not created.

6. Choice 2 will allow you to edit contents of an existing file. It has three choices: replace a line, append lines or delete a line in a file.

7. Choice 3 will allow you to open an existing file and save it with a different name keeping the original file intact.

8. Choice 4 will search for a given pattern in a file and display contents of the file with all occurences of the pattern in double curly braces: {{pattern}}.

9. Choice 5 will take 2 existing file names as input and check whether their contents are EXACTLY similar or not. (Even if there's a difference of a space or a newline, the program will consider their contents as different)

10. Choice 6 will take as input a file name and delete the file if it exists.

11. Choice 7 will take as input a file name and diplay its contents on the terminal if it exists.

12. Choice 8 will exit the program.

13. For smooth functioning, enter the inputs as directed.

############################################################
Known limitations of the code: 

1. The program can handle bad inputs and gives appropriate error messages; BUT if by chance it starts behaving unexpectedly after a bad input, just press Enter a few times or run it again.
#############################################################
