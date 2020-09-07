# EDUARDO BRICEÑO DATA 3B
## *****Bash commands*****

### Are linux commands that we use frequently

cd . // enter the directories

cd .. //get out of the directories

cd // enter the directory

ll //it serves to view the directories

ls // to see the existing files

mkdir // works to create a new directory

top //works to see the programs in progress

pdw // see your directory

nano test.c //it serves to create your file and edit it

gcc // in this you can compile your file

./a.out // runs the files

history // its function is to see all the commands you executed

clear // cleans all written functions

ctrl+x //save your written file

### locate
Search in the computer the word given e.g. locate file1

locate [[:lower:]] word: Search in the computer the given word but in lowercase
### find
It is used to search files in the computer
-find . -name "file name" : Return all the routes where the file is
-find / -name filename: Search the file in the source folder
-find . -atime +100: Shows the files of the folder, that were open 100 days ago -find / -name *.txt -fprint new_file_to_print.txt: Print all the .txt files in the directory specified

### Use of echo command:
You can use echo command with various options. Some useful options are mentioned in the following example. When you use ‘echo’ command without any option then a newline is added by default. ‘-n’ option is used to print any text without new line and ‘-e’ option is used to remove backslash characters from the output. Create a new bash file with a name, ‘echo_example.sh’ and add the following script

## Find Files in Linux, Using the Command Line
Use find from the command line to locate a specific file by name or extension. The following example searches for *.err files in the /home/username/ directory and all sub-directories:

### find . -name testfile.txt
Find a file called testfile.txt in current and sub-directories.

### find . -type f -empty
	Find an empty file within the current directory.

