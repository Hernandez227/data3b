# Erick Hernández DATA 3B## *****Bash commands*****cd . // enter the directories   Example:  cd erick1/erick2/erick3cd .. //get out of the directoriesExample: You are in erick1/erick2/erick3, writte cd.. and you are in erick1/erick2cd // enter the directoryExample: cd erick1/erick2/erick3ll //it serves to view the directoriescat //is to show the elements inside the filetype // it shows what type of file is a filels // to see the existing filesExample: erick1/erick2: erick.c text,txt .hiddenfiles mkdir // works to create a new directoryExample: mkdir erick4ls erick1/erick2: erick.c text,txt .hiddenfiles erick4rmdir //eliminates a directoryExample: rmdir erick4lserick1/erick2: erick.c text,txt .hiddenfiles top //works to see the programs in progresspdw // see your directoryerick1/erick2:nano  //is to create your file and edit itnano fileinc,cgcc // in this you can compile your file./a.out // runs the fileshistory // its function is to see all the commands you executedclear // cleans all written functionsctrl+x //save your written file### locateSearch in the computer the word given e.g. locate file1locate [[:lower:]] word: Search in the computer the given word but in lowercase### findIt is used to search files in the computer-find . -name "file name" : Return all the routes where the file is-find / -name filename: Search the file in the source folder-find . -atime +100: Shows the files of the folder, that were open 100 days ago -find / -name *.txt -fprint new_file_to_print.txt: Print all the .txt files in the directory specified### Use of echo command:You can use echo command with various options. Some useful options are mentioned in the following example. When you use ‘echo’ command without any option then a newline is added by default. ‘-n’ option is used to print any text without new line and ‘-e’ option is used to remove backslash characters from the output. Create a new bash file with a name, ‘echo_example.sh’ and add the following script## Find Files in Linux, Using the Command LineUse find from the command line to locate a specific file by name or extension. The following example searches for *.err files in the /home/username/ directory and all sub-directories:## examples:### find -name "*.exe" -type f### find . -name erick.txtFind a file called erick.txt in current and sub-directories.### find /home -iname ### find . -type f -empty	Find an empty file within the current directory.	### find /tmp -type d -empty