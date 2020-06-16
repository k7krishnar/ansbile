# ansbile
ansible playbooks

I'm trying to document the playbook which will be used frequenty so i don't have to google them again.

For adding users, i'm keeping the generated public keys inside the playbook directory (you can generate on fly as well). And general configs goes under ~/ansible.cfg
and inventory in file "hosts"

To make dry-run
ansible-playbook playbook/add_user.yaml  -i hosts --check

To execute the playbook
ansible-playbook playbook/add_user.yaml  -i hosts
