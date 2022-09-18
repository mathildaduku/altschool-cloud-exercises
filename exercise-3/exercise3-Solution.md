## USERS AND GROUPS

The /etc is a directory in the linux file system that contains configuration files for the file system such as the /etc/passwd file, amongst others. The /etc/passwd is a column-separated file in the linux OS. The components of the column includes: username, password, user ID, group ID, comment, user home directory and user shell.

In this exercise, 3 groups were created, the groups are- admin, support and engineering. The admin group was added to sudoers. The term sudoers mean super user doers which is basically a group of users with administrator access. Users added to this group can carry out executive tasks that regular users would normally not be able to achieve. 

A user was added to the 3 groups created in this exercise. Jessica, lois and alex were added to admin, support and engineering respectively. SSH keys was generated for the user in the admin group, jessica. SSH simply mean secure shell. It is a more secure way of accessing a server. Two keys are generated - a public key and private key. They typically come in pairs and it is more secure than utilizing a password.

The following images show the output of the exercises after carrying out the instructions given

Here is an image showing the content of /etc/passwd file 
![/etc/passwd content](./images/Screenshot%20(30).png)

Here is an image showing the content of /etc/group
![/etc/group content](./images/Screenshot%20(31).png)

Here is an image showing the content of /etc/sudoers
![/etc/sudoers content](./images/Screenshot%20(32).png)