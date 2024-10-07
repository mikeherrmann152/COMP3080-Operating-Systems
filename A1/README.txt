Michael Herrmann
michael_herrmann@student.uml.edu
COMP3080
Assignment1

Success Rate: 100%

This program uses several C language system calls. The first one being the parent process.
Which prints out information about itself. A pipe is then created to synchronize between
parent and child processes. After this a fork() is called. Of which then the child prints
out information about itself and goes into a long loop waiting to get the terminating 
signal from the parent. The parent uses the kill system call on the child which forces
it into its sig_handler function which then executes the Profs Assign1 program.
This then also enters a long lasting loop until the user enters the kill command.

NOTE: After the user inputs the kill command, it does take a while for the program to 
	actually terminate and exit.
