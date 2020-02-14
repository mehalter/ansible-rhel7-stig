# ansible-rhel7-stig

This is a work in progress of an Ansible playbook that will audit and harden
RHEL7 to the DoD STIG v2r6.

This is heavily based on the [MindPointGroup/RHEL7-STIG](https://github.com/MindPointGroup/RHEL7-STIG) Ansible role

## Rules to Investigate Manually

| Severity | Vulid   | STIG-ID        |
|----------|---------|----------------|
| CAT-II   | V-71965 | RHEL-07-010500 |
| CAT-II   | V-92255 | RHEL-07-020019 |
| CAT-II   | V-71971 | RHEL-07-020020 |
| CAT-II   | V-71973 | RHEL-07-020030 |
| CAT-II   | V-71975 | RHEL-07-020040 |
| CAT-I    | V-71997 | RHEL-07-020250 |
| CAT-II   | V-71999 | RHEL-07-020260 |
| CAT-II   | V-72003 | RHEL-07-020300 |
| CAT-I    | V-72005 | RHEL-07-020310 |
| CAT-II   | V-72007 | RHEL-07-020320 |
| CAT-II   | V-72009 | RHEL-07-020330 |
| CAT-II   | V-72011 | RHEL-07-020600 |
| CAT-II   | V-72015 | RHEL-07-020620 |
| CAT II   | V-72227 | RHEL-07-040180 |
| CAT II   | V-72229 | RHEL-07-040190 |
| CAT II   | V-72231 | RHEL-07-040200 |
| CAT II   | V-72269 | RHEL-07-040500 | not sure if you are using chrony or ntp
| CAT III  | V-72881 | RHEL-07-040600 | not sure what the dns solution is
| CAT III  | V-72305 | RHEL-07-040720 |
| CAT III  | V-72307 | RHEL-07-040730 |
| CAT III  | V-72311 | RHEL-07-040750 |
| CAT III  | V-72315 | RHEL-07-040810 |
| CAT III  | V-72317 | RHEL-07-040820 |
| CAT III  | V-72319 | RHEL-07-041001 |
| CAT III  | V-72417 | RHEL-07-041002 |
| CAT III  | V-72427 | RHEL-07-041003 |
| CAT III  | V-72433 | RHEL-07-041010 |