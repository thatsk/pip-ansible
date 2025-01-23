# setup-ansible
A GitHub Workflow action to set up Ansible.

# Usage

```yaml
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
    
      - name: "Install Ansible"
        uses: thatsk/pip-ansible@VERSION 
        with:
          version: "11.1.0"

      - name: "Print Ansible version"
        run: ansible-playbook --version

```
