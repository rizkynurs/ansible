<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Ansible_logo.svg"/>
</p>

## How to run ansible script 

For run the playbook can use this command
```
cd ansible
ansible-playbook -i hosts playbook/{namafile}.yml --ask-pass -K --ask-vault-pass
```