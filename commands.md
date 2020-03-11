Prepare:
ansible-playbook -i ./inventory/arch/hosts playbooks/prepare.yml -k -K -e "ansible_ssh_user=tnguyen" -l vm -v

Run:
ansible-playbook -i ./inventory/arch/hosts playbooks/doomMachine.yml -l vm -v
