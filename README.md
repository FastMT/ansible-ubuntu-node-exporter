# Ansible - Ubuntu Node Exporter


Based on https://github.com/cloudalchemy/ansible-node-exporter

## Installation

Create requirements.yml file

```
# Include ubuntu-node-exporter role
- src: https://github.com/FastMT/ansible-ubuntu-node-exporter.git
  name: ubuntu-node-exporter
  version: "v1.0.3"
```

Install external module into ~/.ansible/roles folder

```
ansible-galaxy install -r requirements.yml
```

## Usage

playbook.yml:

```
# Install node exporter
- role: "ubuntu-node-exporter"
```        