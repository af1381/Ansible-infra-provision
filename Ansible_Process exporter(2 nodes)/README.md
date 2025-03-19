# Note: Before running, please note that you must have already set the ssh-key and the servers must be able to access each other via ssh.

      ansible-playbook -i inventory.yml playbook.yml --ask-become-pass

