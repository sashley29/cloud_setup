### Install ansible for Ubuntu
```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```

### Run playbook locally
`sudo ansible-playbook --ask-vault-pass --connection=local --inventory 127.0.0.1, ansible/playbook.yml
