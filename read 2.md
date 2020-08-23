## the older coder
when he staart searshing about text editor teacher; he find different teachers' style. as he said you can choose text editor which you love and make you enjoyble; there is no the best one
i know will as what is text editor. it is a tool that help develper to manage text to build website; it may be find it online or via application.

###  linux is like windows but it depnds on terminal by doing command line.it make develpers' work easy.However it needs additional practice to be the efficient.
BY linux you can have several command lines open and doing different tasks in each at the same time.

This one can sometimes be hard to get your head around but as you work through the sections it will start to make more sense. A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:

file.exe - an executable file, or program.
file.txt - a plain text file.
file.png, file.gif, file.jpg - an image.

####  This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case.

ls Documents
FILE1.txt File1.txt file1.TXT
...
file Documents/file1.txt
Documents/file1.txt: ERROR: cannot open 'file1.txt' (No such file or directory)


#####paces in names
Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. If we wanted to move into a directory called Holiday Photos for example the following would not work.

ls Documents
FILE1.txt File1.txt file1.TXT Holiday Photos
...
cd Holiday Photos
bash: cd: Holiday: No such file or directory



