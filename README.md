## Role - rol-capg-Database_backup

Role is used to schedule jobs at various hosts. (ENHC0011240 - Database Backup Information requested by Customer)

## Requirements

Add the required hosts in the inventory (AWX Tower)

## Role Variables

Variables in vars/main.yml: hosts_schedule (list variable with different cronjobs)

## Dependencies

None


## Example Playbook

---
- name: Databse Backup Information Automation 
  hosts: all
  gather_facts: true
  roles:
    - rol-capg-Database_backup


## Execution Steps - IMPORTANT

Please add all the required hosts in the inventory (AWX Tower). <br>
Inside databasebackup.yml, "hosts: all" (Therefore, add all the required hosts in the inventory) <br>
After updating the inventory, run the file: "databasebackup.yml" (CLI command: "ansible-playbook databasebackup.yml") <br>

## License

CAPGEMINI CIS

## Author Information

PU Automation.
