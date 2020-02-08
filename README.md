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
| CAT-II   | V-72017 | RHEL-07-020630 |
| CAT-II   | V-72019 | RHEL-07-020640 |
| CAT-II   | V-72021 | RHEL-07-020650 |
| CAT-II   | V-72023 | RHEL-07-020660 |
| CAT-II   | V-72025 | RHEL-07-020670 |
| CAT-II   | V-72027 | RHEL-07-020680 |
| CAT-II   | V-72029 | RHEL-07-020690 |
| CAT-II   | V-72031 | RHEL-07-020700 |
| CAT-II   | V-72033 | RHEL-07-020710 |
| CAT-II   | V-72035 | RHEL-07-020720 |
| CAT-II   | V-72037 | RHEL-07-020730 | Might be able to automate
| CAT-II   | V-72039 | RHEL-07-020900 |
| CAT-II   | V-72043 | RHEL-07-021010 |
| CAT-II   | V-72045 | RHEL-07-021020 | 
| CAT-II   | V-73161 | RHEL-07-021021 |*
| CAT-III  | V-81009 | RHEL-07-021022 |* 
| CAT-III  | V-81011 | RHEL-07-021023 |*
| CAT-III  | V-81013 | RHEL-07-021024 |*
| CAT-II   | V-72047 | RHEL-07-021030 |*
| CAT-II   | V-72049 | RHEL-07-021040 |*
| CAT-III  | V-72059 | RHEL-07-021310 |
| CAT-III  | V-72061 | RHEL-07-021320 |
| CAT-III  | V-72063 | RHEL-07-021330 |
| CAT-III  | V-72065 | RHEL-07-021340 |
| CAT-I    | V-72067 | RHEL-07-021350 |
| CAT-III  | V-72069 | RHEL-07-021600 |
| CAT-III  | V-72071 | RHEL-07-021610 |
| CAT-II   | V-72073 | RHEL-07-021620 |
| CAT-II   | V-72075 | RHEL-07-021700 |
| CAT-I    | V-72213 | RHEL-07-032000 |
| CAT-II   | V-72219 | RHEL-07-040100 |