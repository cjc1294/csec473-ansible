# SSH Setup

Set up SSH and keys with Ansible

 - Requires SSH keys in a sshKeys folder and sshd_config file in the same directory as the playbook
 - Also requires installation of the ansible.posix package
    - Install with "ansible-galaxy collection install ansible.posix"
 - Configure user to install ssh keys on with the target_user variable