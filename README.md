# higher-level-orchestrator
Goal of this project to provide ease of use for repos in this organization

Right now only ansible supported, plan to add Jenkins support in future. 

## Requirements

Install [Ansible](http://docs.ansible.com/ansible/intro_installation.html)

## Run

```shell
git clone https://github.com/roboydk/higher-level-orchestrator.git
cd higher-level-orchestrator/ansible
ansible-playbook playbook.yml -e scheme=scheme.yaml -e topo=topo_10_nodes.yaml
```