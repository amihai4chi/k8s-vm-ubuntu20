

# ansible-vsphere7-k8s

This repository contains an Ansible playbook for creating VMs on vSphere 7, installing Ubuntu 20.04 using a ks.cfg file, and installing Kubernetes and Antrea networking.

## Prerequisites
Please replace the variables in the playbook with your actual values.
- Ansible
- Git

## Usage

1. Clone this repository:
```bash
git clone https://github.com/amihai4chi/ansible-vsphere7-k8s.git

2. Navigate to the repository directory:
cd ansible-vsphere7-k8s
****
3. Run the Ansible playbook:
ansible-playbook playbook.yml
