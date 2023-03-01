## Prerequisites

* ansible
```shell
sudo dnf install ansible
```

* Docker SDK for Python
```shell
pip install docker
```

## Configuration
define `owner`/`group` in `playbook/build.yml`

## Usage
```shell
ansible-playbook -i inventory/inventory.yml playbook/build_send.yml --ask-pass
```

## Used plugin

* [community.general.docker_image](https://docs.ansible.com/ansible/2.10/collections/community/general/docker_image_module.html) 