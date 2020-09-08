# Ansible Role: SSH

## Role Variables

Available variables are listed below.

	ssh_default_private_key: id_rsa
    ssh_public_key_path: id_rsa.pub
    ssh_manual_public_keys:
    ssh_gitlab_usernames:
    ssh_username:
    ssh_user_groups:

Path of a key pair, which are generated by command `ssh-keygen`

    ssh_gitlab_usernames:

A list of gitlab usernames, who setuped ssh key on their account.

## Example of Playbook

	- hosts: all
	  roles:
	    - role: thuvh.ssh
