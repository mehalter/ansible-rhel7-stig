# ansible-rhel7-stig

This is a work in progress of an Ansible playbook that will audit and harden
RHEL7 to the DoD STIG v2r6.

This is heavily based on the [MindPointGroup/RHEL7-STIG](https://github.com/MindPointGroup/RHEL7-STIG) Ansible role

## Rules to Investigate Manually

| Severity | Vulid   | STIG-ID        |
|----------|---------|----------------|
| CAT-II   | V-71965 | RHEL-07-010500 |
|----------|---------|----------------|
| CAT-II   | V-71971 | RHEL-07-020020 |