# ansible-home-lab

This project will contain playbooks that I use to configure my home lab. 

## Sections

### Tools

- Ansible
- Ansible AWX (Upstream of Ansible Automation Platform)

### Installation
This repository is built to be used by AWX so most of the configuration will lie within the application. If the plan is to use this repository on the command line, then put the configuration within the `$HOME/.ansible` directory or `$HOME/.ansible.cfg` file.

### Project Layout

#### Execution Environment
All files and configurations that are needed for a custom execution environment can be found within the `ee` directory within this repository.

#### Playbooks
All playbooks should go into the `playbooks` directory.

#### Host / Group Variables
Ultimately variables should live within the Ansible AWX application. If a variable needs to live within this project, then please place them in a file into the appropriate directories: `group_vars` and `host_vars`.