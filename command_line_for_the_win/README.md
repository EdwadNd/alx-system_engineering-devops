### command_line_for_the_win
 ## General
 A README.md file, at the root of the folder of the project, is mandatory
 This project will be manually reviewed.
 As each task is completed, the name of that task will turn green
 Create a screenshot, showing that you completed the required levels
 Push this screenshot with the right name to GitHub, in either the PNG or JPEG format
## Complete the first 9 tasks.

answers: 
Print the Lines with Particular String in File Linux-2

There is a file named access.log in the current working directory. Print all lines in this file that contains the string "GET".

grep  "GET" access.log 

Print all files in the current directory, one per line (not the path, just the filename) that contain the string "500".

grep -rl "500"

Print the relative file paths, one path per line for all filenames that start with "access.log" in the current directory.

find . -name 'access.log*'

Print all matching lines (without the filename or the file path) in all files under the current directory that start with "access.log" that contain the string "500".

Note that there are no files named access.log in the current directory, you will need to search recursively.

 grep -r -h "500"

 Extract all IP addresses from files that start with "access.log" printing one IP address per line.

 grep -ro ^[0-9.]*

 Count the number of files in the current working directory. Print the number of files as a single integer.

 ls -l | wc -l

Print the contents of access.log sorted.

 sort access.log

Print the number of lines in access.log that contain the string "GET".

 grep -c GET access.log

  The file split-me.txt contains a list of numbers separated by a ; character.
Split the numbers on the ; character, one number per line

tr ';' '\n' < split-me.txt


Print the numbers 1 to 100 separated by spaces.

echo {1..100}
