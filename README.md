# Ansible Playbook for Server Daily Check

This is some playbook for database server daily check, especially Oracle and Postgres server running on RHEL.
The playbook contains scripts for checking date, disk usage, backup status, Oracle listener and database background process.
When the playbook run, it will write the PLAY RECAP into log named ansible.log file then email it to administrator.
This playbook run daily and automatically with the help of cron job schedule.
