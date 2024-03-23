Web Stack Debugging #1

Description

This project aims to troubleshoot and resolve an issue with an Nginx installation on an Ubuntu container not listening on port 80. By using debugging techniques and scripting, the goal is to automate the fix to ensure Nginx is properly configured to listen on port 80 of all active IPv4 IPs.

Requirements

Allowed editors: vi, vim, emacs
All files will be interpreted on Ubuntu 20.04 LTS
All files should end with a new line
A README.md file at the root of the project folder is mandatory
All Bash script files must be executable
Bash scripts must pass Shellcheck without any error
Bash scripts must run without error
The first line of all Bash scripts should be exactly #!/usr/bin/env bash
The second line of all Bash scripts should be a comment explaining what the script is doing
You are not allowed to use wget

Tasks

Task 0: Nginx likes port 80
Description: Using debugging skills, identify and resolve the issue causing Nginx not to listen on port 80. Write a Bash script to automate the fix.

Requirements:

Nginx must be running and listening on port 80 of all the server’s active IPv4 IPs
Write a Bash script that configures a server to meet the above requirements
Script Usage
To use the provided Bash script for fixing the Nginx port 80 issue:

Clone this repository:
git clone https://github.com/alu-system_engineering-devops/web_stack_debugging_1.git

Navigate to the project directory:
cd web_stack_debugging_1

Ensure the script is executable:
chmod +x 0-nginx_likes_port_80

Execute the script:
./0-nginx_likes_port_80


Author
Chol Daniel
