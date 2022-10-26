## ANSIBLE

Ansible is a software that helps automate tasks and configurations to servers. It is lightweight,  agentless, and easy to use. It is written in YAML.
A playbook witten in yaml is used to run ansible. It is the cummulation of all the hosts and tasks. The server where ansible is installed is the control server, this is where the groundwork will be done, instructions will be deployed to other servers from here.
The servers recieving the instructions are called the target servers, they are listed in the playbook under the host header and can be identified by their ip address or domain name. 

In this exercise, an ansible playbook was created to setup a server with apache, the server timezone was set to Africa/Lagos. An index.php file was hosted as the main file on the server, which displayed the date. 

Below are images showing the ansible playbook, the output of <code>systemctl status apache</code> after deploying the playbook and screenshots of the rendered page, respectively.
![Playbook](./images/Screenshot%20(85).png)

![Deployed playbook](./images/Screenshot%20(71).png)

![output of systemctl status apache](./images/Screenshot%20(68).png)

![Rendered apache page](./images/Screenshot%20(70).png)

![Rendered index.php page](./images/Screenshot%20(69).png)