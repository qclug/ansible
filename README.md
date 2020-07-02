# ansible
Ansible repo for QCLUG demos

## Installation
First clone this repo
```
git clone https://github.com/qclug/ansible.git qclug-ansible
cd qclug-ansible
```
Create a virtualenv, you could use something like `pyenv` if you'd prefer
```
virtualenv -p $(which python3) venv
source venv/bin/activate
```
Install ansible
```
pip install ansible
```
Install dependent roles
```
ansible-galaxy install -r requirements.yml -p ./roles
```
