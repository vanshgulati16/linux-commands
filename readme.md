# Linux Commands

### Updated everyday

`whoami`: Gives detail about the user login as. <br>
`whoami `

`man`: Tells about the commands. <br>
`man <command name>`

`clear`: Clear the terminal. <br>
`clear`

`pwd`: Tells the location we currently in. <br>
`pwd`

`ls`: List the content of a folder. <br>
`ls <file name>`<br>
`ls -a`: To explore all the files even hidden one's. <br>
`ls -l`: To expand and see all the details of the file/folders like dates etc. <br>
`ls -al`: To expand and show all the file/folders. <br>

`cd `: To move from one to another file. <br>
`cd <file name>` <br>

`mkdir`: Makes a new directory. <br>
`mkdir fruit panda`: will make two directories named as fruit and panda. <br>
`mkdir -p fruit/panda`: make a nested directory. <br>

`rmdir`: remove empty directory. <br>
`rmdir fruits cars`: removing mutiple empty directory. <br>

`touch`: to make some files. <br>

`rm`: to remove files and folders.  <br>
`rm -v `: tell us what did it do. <br>
`rm -r`: to remove directories. <br>
`rm -ri`: interactively remove files. <br>
`rm fruit car`: delete folders with files in them. <br>

`open`: open the directories. <br>
`open .`: to open current directory. <br>

`mv`: to move directory.<br>
`mv open open_pear`: this command can change up file name from pear to open_pear. <br>
`mv open stuff`: move from one directory to another. <br>

`cp`: Copy files.<br>
`cp journel.txt new_jounel.txt`: To make a copy in the same directory. <br>
`cp -r <filename>`: to copy a directory. <br>

`head`: Outputs the top 10 lines in a file. <br>
`head file.txt -n 100`: To print out the top 100 lines of the file. <br>

`tail`: outputs the last 10 lines of a file.<br>

`>`: to get the output of a command in a file. <br>
`pwd > today.txt`: it saves the output in today.txt file, but this command just replaces the content of the file <br>
`Note`: if the file does not exist in the directory, no problem it will create the file and store the output. <br>
`>>`: If we use a double right arrow then the content in the file will be updated line by line. <br>

`cat`: Concatinate <br>
`cat <filename>`: this will print out the contents of the file. <br>
`cat <filename1> <filename2>`: concatenate both the files and print out both file's contents. <br>
`cat file1 file2 file3 > fileEverything`: It concatenates all the file's content into one file, here that is fileEverting. <br>

`less`: Gives an interactive overview of the content saved inside the file. <br>
`less file`: Gives an interactive vire of the content and we can search words also. <br>

`echo`: Prints the txt file or text that is been provided. <br>
`echo hello`: print hello <br>
`echo "hello" > anyfilename.txt`: this command puts the hello command in a file called anyfilename.txt, if the file does not exist then  it would make a file named after what we mentioned. <br>

`wc`: Word Count.
` wc -l`: No of lines <br>
`wc -w `: No of words <br>

  `Pipeping`:
  `ls -l | wc`: This would count the no of lines, words that are been listed by ls -l. <br>
  `cat file1.txt file2.txt | wc > wordcountfile.txt `: It concatenates the content of file1 and file2 and gives a word count of it and stores the word count to a file name wordcountfile.txt.. <br>




