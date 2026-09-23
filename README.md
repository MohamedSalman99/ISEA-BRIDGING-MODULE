# ISEA-BRIDGING-MODULE

## Session 1a – Setting Up Linux

### Ubuntu Virtual Machine Setup

I used Oracle VirtualBox to create and run an Ubuntu virtual machine. This provided an isolated Linux environment where I could complete the Linux and server administration lab activities.

**What I learned:**  
I learned how virtualisation can be used to run Ubuntu without replacing the operating system on my main computer. The virtual machine provided a safe environment for practising Linux commands and server configuration.

### Basic Linux Command-Line Navigation

I practised basic Linux commands to navigate and manage the filesystem. I used `pwd` to display my current directory, `ls` to list files and directories, `mkdir` to create a new directory, `cd` to enter the directory, and `touch` to create a new file.

**What I learned:**  
This activity helped me understand how files and directories can be created and managed directly through the Linux command line. These commands provide the basic foundation for navigating and managing a Linux server.

### Linux Manual Pages

I used the `man ls` command to view the Linux manual page for the `ls` command. The manual provides information about the purpose, syntax and available options for Linux commands.

**What I learned:**  
I learned that the `man` command provides built-in documentation that can be used to understand Linux commands and their available options.

## Session 1b – Exploring Linux

### Managing Linux Services

I used `systemctl` to check the status of the SSH service. The initial status showed that SSH was inactive, so I started the service using `sudo systemctl start ssh`. I then checked the status again and confirmed that the SSH service was active and running.

**What I learned:**  
I learned that installing a Linux service does not necessarily mean that it is currently running. I used `systemctl` to check and start the SSH service, which helped me understand how Linux background services can be managed and troubleshooted.

### Linux File Permissions

I used `ls -l` to view the permissions of a file and `chmod 755` to modify its permissions. I also used `chown` to set the owner and group of the file.

**What I learned:**  
I learned how Linux file permissions control who can read, write and execute files. The `755` permission gives the owner read, write and execute access, while the group and other users receive read and execute access. I also learned that `chown` can be used to manage file ownership.

### Searching Files and File Contents

I used `find` to locate a file within the Linux filesystem and `grep` to search for specific text inside the file. I first added text to a test file and then used both commands to verify that the file and its contents could be located successfully.

**What I learned:**  
I learned that `find` is useful for locating files based on criteria such as their name, while `grep` can search for specific text within files. These commands can be useful when searching configuration files, logs and other files during Linux system administration.

## Session 2b – Cloud Services

### AWS EC2 Ubuntu Server

I created an Ubuntu cloud server using Amazon EC2. I configured the instance using a free-tier eligible `t3.micro` instance type, created an SSH key pair for authentication, and configured the security group to allow SSH and HTTP traffic.

**What I learned:**  
I learned how a virtual Linux server can be deployed in a cloud environment using AWS EC2. I also learned that security groups control the network traffic that is allowed to reach the cloud server.

### Connecting to the EC2 Server Using SSH

I connected remotely to the Ubuntu EC2 instance using SSH and the private key that was created when the instance was launched. I used basic commands to confirm the logged-in user, hostname and current working directory.

**What I learned:**  
I learned how SSH can be used to securely access and manage a remote Linux server. I also learned how SSH key-based authentication can be used instead of a password when connecting to a cloud server.
