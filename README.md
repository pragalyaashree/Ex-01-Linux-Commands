# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which

helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="454" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/193b465b-020e-4e22-9c11-fc8ebe853be6">

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="450" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/d736c94c-7e42-4e1e-b62f-a5b3c6aec374">

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="453" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/a27ba064-d4ee-4897-9aaa-85bce147f5fa">

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="452" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/afc1472d-b4f1-41e5-ae2b-ed7c0060c6d3">

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="450" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/700c965f-dc70-49cd-bb56-a6442ef441fd">

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 <img width="450" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/3af268e2-cb33-428a-94b0-69392e995d1c">

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="451" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/7ffd5e77-69a4-41f2-bd99-489baa683a1e">

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="451" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/9fcf1a36-eb25-4cbb-8eb8-34bad72ecf82">

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="448" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/b9910f13-958e-42ca-aaba-b98397e077d4">

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="453" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/0aa6cbe5-3f53-49a5-ba16-803159fd1f24">

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="453" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/35eaad4a-6b5f-4223-9846-1fb37bd2a6b3">

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="403" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/f7361456-e66f-4883-ba85-3ea16c7a5b5b">

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 <img width="452" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/bdeda8b9-d3f1-4ee9-9a81-50a5560ca0a5">

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="452" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/886d84a9-dc84-4f80-96e4-5797d8ea948c">

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="454" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/32865662-8467-422e-8679-e4f6d07c9731">

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="452" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/7bed15ec-c773-47e7-92fd-2c9e11851a04">

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="453" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/45e0f343-1168-4b7d-91c9-d449f37126c7">

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="447" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/538624cd-6420-4090-ba7c-8c6ecb8fd128">

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="452" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/23516c8a-7faa-473e-b05f-ed8ef2bf1d94">

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="449" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/2974dc60-101f-4355-9a8d-99b50c55f5cb">

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="451" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/708a6bb1-ca0e-464a-9137-5cd7f03b91b9">

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="426" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/5120eec6-11cf-4e29-9251-46a5057a66e5">

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="449" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/53435758-10e7-448b-9923-4bf9edf8cd33">

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="452" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/59684264-881c-45f5-bb64-6168409246db">

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="449" alt="image" src="https://github.com/Catty12384/Ex-01-Linux-Commands/assets/120629225/361b7d94-4714-4aca-afd1-73631648c754">

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.


















