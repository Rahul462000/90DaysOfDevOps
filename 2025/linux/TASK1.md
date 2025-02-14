# 🚀 Project: DevOps Linux Server Monitoring & Automation

# Task 1 : User & Group Management.

## Objective

1.Create a user devops_user and add them to a group devops_team.<br>
2.Set a password for devops_user and grant sudo access. <br>
3.Restrict SSH login for certain users in /etc/ssh/sshd_config. <br>

1.1 Create a user devops_user and add them to a group devops_team.<br>
`sudo useradd devops_user`

1.2 setting password for the user created above<br>
`passwd devops_user`

1.3 creating group devops_team<br>
`sudo groupadd devops_team`

1.4 adding devops_user to group devops_team<br>
`sudo groupadd devops_user devops_team`

1.5 to check if user is added to a specific group<br>
`id -Gn devops_user`

1.6 granting sudo access to devops_user<br>
`sudo usermod -aG sudo devops_user`

1.7 REstricting SSH login for certain user eg devops_user <br>

- first redirect to this path /etc/ssh/ssh_config
- use command `DenyUsers devops_user`
- restart the system by command `sudo systemctl restart sshd`
