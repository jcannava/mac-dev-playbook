# Ansible playbook for setting up development on a Mac
- Ensure Apple's command line tools are installed (xcode-select --install)
- Install Ansible (pip install ansible)
- Clone this repo
- mkdir -p ~/.ansible/roles
  (*note: export ANSIBLE_ROLES_PATH=~/.ansible/roles)
- Run ansible-galaxy install -r requirements.yml
- Run ansible-playbook main.yml -i inventory -K (enter account password when prompted)
