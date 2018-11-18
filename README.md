# dev-environment-automation

An ansible based automation script to install all the configurations
I like for my personal terminal (bash/zsh) dev environment

## How to use

To get the environment setup locally, `Ansible` must already be installed,
check [here](https://docs.ansible.com/ansible/2.5/installation_guide/intro_installation.html) for a guide

To run locally run the following command:

```sh
ansible-playbook --connection=local --inventory 127.0.0.1, index.yaml
```

currently `apt` is the package manager that is supported but others can be easily swapped
