# **Basic Shell Scripts**

* [0-current_working_directory](0-current_working_directory) : a script that prints the absolute path name of the current working directory.
* [1-listit](1-listit) : Display the contents list of your current directory
* [2-bring_me_home](2-bring_me_home) : a script that changes the working directory to the user’s home directory
* [3-listfiles](3-listfiles) : Display current directory contents in a long format
* [4-litsmorefiles](4-listmorefiles) : Display current directory contents, including hidden files (starting with .). Use the long format.
* [5-listfilesdigitonly](5-listfilesdigitonly) : Display current directory contents.
    >+ Long format
    >+ with user and group IDs displayed numerically
    >+ And hidden files (starting with .)

* [6-firstdirectory](6-firstdirectory) :  a script that creates a directory named **my_first_directory** in the **/tmp/** directory.
* [7-movethatfile](7-movethatfile) : Move the file **betty** from **/tmp/** to **/tmp/my_first_directory**.
* [8-firstdelete](8-firstdelete) : Delete the file **betty**.
    >+ The file **betty** is in **/tmp/my_first_directory**
* [9-firstdirdeletion](9-firstdirdeletion) : Delete the directory **my_first_directory** that is in the **/tmp** directory.
* [10-back](10-back) : a script that changes the working directory to the previous one.
* [11-lists](11-lists) : a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the **/boot** directory (in this order), in long format.
* [12-file_type](12-file_type) :  a script that prints the type of the file named **iamafile**. The file **iamafile** must be in the **/tmp** directory when you run the script.
* [13-symbolic_linl](13-symbolic_link) : Create a symbolic link to **/bin/ls**, named **\_\_ls__**. The symbolic link should be created in the current working directory
* [14-copy_html](14-copy_html) :  a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
* [100-lets_move](100-lets_move) :  a script that moves all files beginning with an uppercase letter to the directory **/tmp/u**.
* [101-clean_emacs](101-clean_emacs) : a script that deletes all files in the current working directory that end with the character **~**.
* [102-tree](102-tree): Create a script that creates the directories **welcome/**, **welcome/to/** and **welcome/to/school** in the current directory.
* [103-commas](103-commas): Write a command that lists all the files and directories of the current directory, separated by commas (,).
    >+ Directory names should end with a slash (/)
    >+ Files and directories starting with a dot (.) should be listed
    >+ The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
    >+ Only digits and letters are used to sort; Digits should come first
    >+ You can assume that all the files we will test with will have at least one letter or one digit
    >+ The listing should end with a new line
* [school.mgc](school.mgc) : a magic file **school.mgc** that can be used with the command file to detect **School** data files. **School** data files always contain the string **SCHOOL** at **offset 0**.