# ansible_netbox
ansible netbox lab
ansible-galaxy collection install cisco.ios

ansible-galaxy collection install netbox.netbox
ansible-inventory -v --list -i netbox_inv.yml

ansible-playbook create_configs.yml
