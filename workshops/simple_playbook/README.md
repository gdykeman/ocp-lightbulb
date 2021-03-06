# Workshop: Simple Playbook

### Topics Covered

* Using `ansible-playbook`
* YAML syntax basics
* Basic Ansible playbook structure
* Tasks and modules

### What You Will Learn

* How to use `ansible-playbook`
* The basics of YAML syntax and Ansible playbook structure

### The Assignment

Create an Ansible playbook that targets members of the "web" group has the following state:

1. The nginx package is present using yum
1. Has the homepage that is provided in `resources/`.
1. Nginx is started on each host.

While developing the playbook use the `--syntax-check` to check your work and debug problems. Run your playbook in verbose mode using the `-v` switch to get more information on what Ansible is doing. Try `-vv` and `-vvv` for added verbosity. Also consider running `--check` to do a dry-run as you are developing. 

#### NOTE

You will need to make sure each host in web has setup the EPEL repo to find the nginx package.

### Resources

* [YAML Syntax](http://docs.ansible.com/ansible/YAMLSyntax.html)
* [Intro to Ansible Playbooks](http://docs.ansible.com/ansible/playbooks_intro.html)
* [yum module](http://docs.ansible.com/ansible/yum_module.html)
* [file module](http://docs.ansible.com/ansible/file_module.html)
* [service module](http://docs.ansible.com/ansible/service_module.html)
