# Jenkins
Jenkins installation using Ansible

# Requirements



Add below line into /etc/sudoers on target machine after "Same thing without a password"

jainendra ALL=(ALL) NOPASSWD: ALL

Open the 8080 port on the target machine by going into /etc/sysconfig/iptables

# Dependencies

Java

How to run Playbook

	[jainendra@centos66 Jenkins]$ ansible-playbook  site.yml -i inventory/jenkins-servers
License

NA

Author Information

NA
