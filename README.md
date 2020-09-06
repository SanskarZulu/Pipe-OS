# Pipe-OS
Problem statement: 
Design a program using ordinary pipes in which one process sends the string message to a second process, and the 
second process reverses the case of each character in the message and sends it back to the first process. 
For example, if the first process sends the message Hello Friends, the second process will return hELLO fRIENDS.

/*
Output of the code: 
Trail 1::

sanskar@sanskar-VirtualBox:~$ gcc OSPipe.cpp -o Trial1
sanskar@sanskar-VirtualBox:~$ ./Trial1 "Hi, I am Sanskar Sharma. So You MuST be ThINKing WhYY i StarTed cHangiNG caSE."

		OS Lab Assignment by Sanskar Sharma 0120180381

	Parent(7296): Sending { Hi, I am Sanskar Sharma. So You MuST be ThINKing WhYY i StarTed cHangiNG caSE. } to Child

	Child(7297): Recieved Message

	Child(7297): Toggling Case and Sending to Parent

	Parent(7296): Received { hI, i AM sANSKAR sHARMA. sO yOU mUst BE tHinkING wHyy I sTARtED ChANGIng CAse. } from Child

sanskar@sanskar-VirtualBox:~$ 

Trial 2:

sanskar@sanskar-VirtualBox:~$ gcc OSPipe.cpp -o Trial2
sanskar@sanskar-VirtualBox:~$ ./Trial2 "i AM 20 YEARS OLD."

		OS Lab Assignment by Sanskar Sharma 0120180381

	Parent(7381): Sending { i AM 20 YEARS OLD. } to Child

	Child(7382): Recieved Message

	Child(7382): Toggling Case and Sending to Parent

	Parent(7381): Received { I am 20 years old. } from Child

sanskar@sanskar-VirtualBox:~$ 

Trial 3:

sanskar@sanskar-VirtualBox:~$ gcc OSPipe.cpp -o Trial3
sanskar@sanskar-VirtualBox:~$ ./Trial3 1+@#+@6+*

		OS Lab Assignment by Sanskar Sharma 0120180381

Sorry, The string you entered did NOT contain any Alphabetical Characters
Run me again, with at least 1 Alphabetical character

sanskar@sanskar-VirtualBox:~$ 

Trial 4:

sanskar@sanskar-VirtualBox:~$ gcc OSPipe.cpp -o Trial4
sanskar@sanskar-VirtualBox:~$ ./Trial4 Okay another Try

		OS Lab Assignment by Sanskar Sharma 0120180381

Usage: ./Trial4 <string> or <'string 1, string 2', ..., string n'> for multiple strings
sanskar@sanskar-VirtualBox:~$ 

*/
