# prelim_special

Create the following network topology in VirtualBox. You can use Ubuntu as your preferred OS. 
On Server 1 and 2, edit the hostname to server1 and server2 respectively. Also, edit the hosts and change the workstation name to server1 and server2 respectively. Reboot both servers. 
On Server 1 and 2, do the following:
update and upgrade the servers
install openssh-server
verify if the SSH server has started for
configure the firewall allowing port 22
Record the IP address of Server 1, 2, and the local machine. 
Connectivity test from local machine to Server 1
Connectivity test from local machine to Server 2
Connectivity test from Server 1 to local machine
Connectivity test from Server 2 to local machine
Connectivity test from Server 1 to Server 2
Connectivity test from Server 2 to Server 1
Verify SSH connectivity:
SSH from local machine to Server 1
SSH from local machine to Server 2
On the local machine, create an SSH key pair for user authentication: use the command ssh-keygen -t rsa -b 4096
On the local machine, copy the public key (id_rsa.pub) to Server 1 and 2
On the local the local machine, install git. 
Go to your GitHub account and do the following: 
Create a repository and named it as prelim_special
Add a README.md file. 
On your GitHub settings, delete your previous SSH key (if you have), and create a new SSH key. Copy the public key and paste it here.
Clone the repository you created. You may copy the SSH link of the repository you created and paste it on the command to clone the repository on your local machine. 
Personalize your git (name and email address). 
Edit your README.md file. Copy the text of all the instructions of the special exam and paste it on your markdown file. Do the following:
Verify git status
Add README.md file to the staging area
Commit the changes
Push the changes to the remote repository (GitHub)
On GitHub, show the changes, commit and text of the README.md file.
