# Ansible-local-config
Install and update my applications in my pc

## Command to execute ##
ansible-playbook -b --connection=local --inventory 127.0.0.1, -e 'ansible_python_interpreter=/usr/bin/python3' site.yml -K
