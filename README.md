# 📕 CENTOS 8 Cloud-Init DevBox Playbook

An Ansible playbook designed to set up a development environment on CentOS 8 using cloud-init. This playbook aims to automate the provisioning of a CentOS 8 virtual machine or cloud instance, specifically tailored for development purposes. It includes tasks to install common development tools and perform other necessary configurations to create a functional and ready-to-use development environment.

## 🗂️ The files structure is organised this way:
Based on [Ansible Best Practices: Sample directory layout](https://docs.ansible.com/ansible/latest/tips_tricks/sample_setup.html#sample-directory-layout)

## 🚀 Quick start

1. `git clone` this repository.
2. Go to the cloned folder.
3. Select a playbook (see [`Available playbooks`](https://github.com/truewebartisans/useful-playbooks#-available-playbooks) section).
4. Run `<playbook_name>` -i `<inventory_name>` --ask-become

Example

```console
ansible-playbook new-localhost-server.yml -i dev.ini --ask-become
```

## 📚 Available playbooks

- 📖 `localhost.yml` For auto configure a fresh localhost virtual server, one limitation of this playbook is that it requires a manual reboot after execution.

- 📖 `site.yml` For auto configure a fresh remote virtual server.

## ⚠️ License

MIT / BSD

## 🇬🇧🇭🇰 Author Information

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Website: https://www.jodywan.com