## APPLICATION PACKAGE MANAGEMENT
In this exercise PHP7.4 was installed using the ppa:ondrej/php package repository. In linux, packages can be gotten from repositories hosted on remote servers from which the local system retrieves and installs software and updates. These repositories are listed in the /etc/apt/sources.list file and the /etc/apt/sources.list.d/ directory on the local system. There are some essential software repos already contained in this local file and directory, however new software packages can be added to it. This brings us to PHP7.4 which we installed. Repositories can be installed by:
<ol>
<li> Manually editing the /etc/apt/sources.list file or /etc/apt/sources.list.d directory. This is done by adding the repository directly to the file after which an apt update will be done to make the system aware of the newly added repository then installation can proceed.</li>
<li> Using the add-apt-repository command. Apt  stands for application package tool. The syntax for this command is <code>add-apt-repository OPTION REPOSITORY</code> or <code>add-ppa-repository ppa:USER/NAME</code>.
Ppa repository is a repository generally owned personally or by a group of independent developers. USER is the ppa username created by launchpad while NAME is the PPA name where a single user may provide multiple ppa repositories.</li>
</ol>

The images below show the content of /etc/apt/sources.list, /etc/apt/sources.list.d and the output of php-v command respectively after installing php7.4.

![/etc/apt/sources.list file](./images/Screenshot%20(34).png)

![/etc/apt/sources.list.d directory](./images/Screenshot%20(35).png)

![php-v command output](./images/Screenshot%20(33).png)