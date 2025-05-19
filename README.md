<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Ansible_logo.svg"/>
</p>

## How to run ansible script 

- Change `inventory` in ansible.cfg with your environment
- Add host for run the playbook
- Change the host for each playbook
- For run the playbook can use this command
```bash
cd ansible
ansible-playbook -i hosts playbook/{namafile}.yml --ask-pass -K --ask-vault-pass
```