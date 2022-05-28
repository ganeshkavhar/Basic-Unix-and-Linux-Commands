# Basic-Unix-and-Linux-Commands
Learning unix operating system is very easy. It is just that you need to understand the unix server concepts and familiar with the unix commands. Here I am providing some important unix commands which will be used in daily work.

Unix Commands With Examples:

1. Listing files

The first thing after logging into the unix system, everyone does is listing the files in a directory. The ls command is used to list the files in a directory.

>ls

add.sh
logfile.txt
prime.pl

If you simply execute ls on the command prompt, then it will display the files and directories in the current directory.

>ls /usr/local/bin

You can pass a directory as an argument to ls command. In this case, the ls command prints all the files and directories in the specific directory you have passed.

2. Displaying the contents of a file.

The next thing is to display the contents of a file. The cat command is used to display the contents in a file.

>cat file.txt
This is a sample unix file
Learning about unix server is awesome

3. Displaying first few lines from a file.

The head command can be used to print the specified number of lines from the starting of a file. The below head command displays the first five lines of file.

>head -5 logfile.dat

4. Displaying last few lines from a file.

The tail command can be used to print the specified number of lines from the ending of a file. The below tail command displays the last three lines of file.

>tail -3 logfile.dat

5. Changing the directories

The cd command can be used to change from one directory to another directory. You need to specify the target directory where you want to go.

>cd /var/tmp

After typing this cd command you will be in /var/tmp directory.

6. Creating a file.

The touch command simply creates an empty file. The below touch command creates a new file in the current directory.

touch new_file.txt

7. copying the contents of one file into another.

The cp command is used to copy the content of source file into the target file. If the target file already have data, then it will be overwritten.

>cp source_file target_file

8. Creating a directory.

Directories are a way of organizing your files. The mkdir command is used to create the specified directory.

>mkdir backup

This will create the backup directory in the current directory.

9. Renaming and moving the files.

The mv command is used to rename the files and it also used for moving the files from one directory into another directory.

Renaming the file.

>mv file.txt new_file.txt

Moving the file to another directory.

>mv new_file.txt tmp/

10. Finding the number of lines in a file

The wc command can be used to find the number of line, words and characters in a file.

>wc logfile.txt
21  26 198 logfile.txt

To know about the unix command, it is always good to see the man pages. To see the man pages simply pass the command as an argument to the man.

man ls
