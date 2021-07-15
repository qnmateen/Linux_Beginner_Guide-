# Linux_Beginner_Guide-

**ls** - list of content.

**cd**	Changes current working directory.   

**mkdir** - make directory.  

**pwd**	Prints working directory.   

**mv** - move    

**cp** -  copy.   

**rm** - remove files   

**cat**	Concatenates files.

**cat file1_name file2_name > new_name**
Unix command **cat** can be used to join two or more files into 1
**>** is used to direct output 

**less**	one page at a time view.  

**head**	Displays the first ten lines of a file.   

**tail**	Displays the last ten lines of a file.   

**find**	Finds files matching an expression.   

**grep**	Searches a file for patterns.   

**wc**	Counts the lines, words, characters, and bytes in a file.  
**ls | wc -l **   
**|** is a pipe character.  
**ls** will list abd **wc** will tell the number of files and **-l** ask wc to return the count of number of lines   

**kill**	Stops a process.   

**jobs**	Lists the processes that are running     

## Running a Bash file.  
bash file.sh

**to run in background**
use **&** symbol at end
bash file.sh &

## Use of nohup.  

**nohup** - nohup is a POSIX command which means "no hang up". Its purpose is to execute a command such that it ignores the HUP (hangup) signal and therefore does not stop when the user logs out. Output that would normally go to the terminal goes to a file called nohup.  
***Example***
nohup gzip filename & > file.log 2>err.log
*> file.log*  output file of nohup
*2> err.log*  output error file

