Descriptions of shell scripts
ls - TO list files in a working directory.
cd ~ - takes user to the home directory.
pwd - diplays ccontent lisst of current directory.
ls -l - Display current directory contents in a long format.
ls -la - Display current directory contents, including hidden files (starting with .). Use the long format.
ls -lan - Display current directory contents.
mkdir /tmp/my_first_directory -  a script that creates a directory named my_first_directory in the /tmp/ directory. 
mv /tmp/betty /tmp/my_first_directory - Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty - Delete the file betty.
rmdir /tmp/my_first_directory - Delete the directory my_first_directory that is in the /tmp directory.
cd - - Write a script that changes the working directory to the previous one.
ls -al . .. /boot - Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile - Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
cp -un *.html ../ - Copy HTML files
mv [[:upper:]]* /tmp/u - HTML  Let’s move.
rm *~ - script that deletes all files in the current working directory that end with the character ~.
