# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Structure
- **inventory/**: Inventory files and group variables
- **playbooks/**: Ansible playbooks
- **roles/**: Custom roles
- **secrets/**: Encrypted secrets (Vault files)
- **logs/**: Logs of playbook runs
- **.env/**: Environment variables for secure configuration

## Usage
1. Install Ansible:
   ```bash
   pip install ansible=={{ cookiecutter.ansible_version }}

