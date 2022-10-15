## CIS security benchmarks

CIS stands for Center for internet security. The CIS provides a baseline of security best practices and configurations that have already been put together by industry experts from various organizations and backgrounds, and most times academia. 

They've prepared the material in form of pdf documents you can download from their websites with recommendations for the basic things you need to configure in your system to make them secure. Most of these configuration are already set in the system but it is alway good to check to make sure you are safe. 

In this exercise, the CIS benchmark for Ubuntu 20.04LTS was used and 10 of the recommendations from the benchmark were implemented. They are listed below;

<ol> 
<li>
Ensure /dev/shm is configured. 

![/dev/shm](./images/Screenshot%20(39).png)

</li>
<li>
Ensure mounting of cramfs filesystems is disabled

![cramfs filesystem](./images/Screenshot%20(44).png)

</li>
<li>
Ensure CUPS is not installed

![CUPS](./images/Screenshot%20(48).png)

</li>
<li>
Ensure NFS is not installed

![NFS](./images/Screenshot%20(52).png)

</li>
<li>
Ensure DNS Server is not installed

![DNS](./images/Screenshot%20(53).png)

</li>
<li>
Ensure journald is configured to compress large log files

![journald system](./images/Screenshot%20(55).png)

</li>
<li>
Ensure rsyslog is installed

![rsyslog](./images/Screenshot%20(58).png)

</li>
<li>
Ensure journald is configured to wite logfiles to persistent disk

![journald](./images/Screenshot%20(59).png)

</li>
<li>
Ensure no duplicate user names exist. 

![bash script](./images/Screenshot%20(63).png)

![bash script executed](./images/Screenshot%20(61).png)

</li>
<li>
Ensure all groups in /etc/passwd exist in /etc/group. 

![Bash script](./images/Screenshot%20(66).png)

![Executed script](./images/Screenshot%20(65).png)

</li>

</ol>