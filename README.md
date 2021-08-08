Bashrc configuration for root and user

-------------------------------------------------------------------------------------------

!!! REMEMBER, this code is available under license Apache-2.0 License.
You are responsible for all the changes you make to your operating system.
No guarantees. Be careful.

-------------------------------------------------------------------------------------------

The .bashrc file is a script file which executed when a user and a root login in bash of Linux.
The file contains a configurations for the terminal session.
This includes : coloring, aliases, completion, functions, and more.

1) First you need to find your .bashrc file.
Find out your linux distribution and read where the file is hidden.

2) Open the file in your editor

Examples of Debian 9:

a) For user:

mcedit ~/.bashrc
OR
vi ~/.bashrc


b) You need the rights of the root:

mcedit /root/.bashrc
OR
vi /root/.bashrc


3) Look at the files 'root_bashrc_updates' and 'user_bashrc_update'.
Transfer the commands you like to your '.bashrc'-file.
And save your .bashrc

4) To reflect the changes in the bash, either exit and launch the terminal again.
OR use the command:

source .bashrc

Enjoy!
