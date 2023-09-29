## DevOps4ML_Linux_task 🚀

### Hands-On-task-Linux

As a junior DevOps engineer, you have a task from Team Lead.

A client wants to have a file filled with commands which they can execute at their side to achieve the next things:
1. All commands below should be executed by user "admin".
2. Create an archive from contents of /etc/nginx/ directory.
3. Move this archive to /opt/archive/ directory.
4. Outputs of all commands should be stored in /opt/archive/output.txt file and must be understandable - the file is created for clients' needs.
5. The "echo" command could help you with that.
6. /opt/archive and all files inside must be owned by user "director" and group "maintainer".

Please keep in mind next things:

- Neither Nginx nor required users or groups are on the newly created instance by default, add them manually. Both output and command files must well-commented to explain what is going on.  
- Pay attention to this page, especially Security Groups (AWS security policy#SecurityGroups)  
- Change default 22 port inbound rule to HTTPS (443) and source IP address should be your public IP Address.  
- Read AWS Instance creation steps to learn how to create an AWS instance, which AMI/IAM to use, etc.  
