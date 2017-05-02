## Synopsis

This is a collection of resources to deploy and configure a 3-node Consul Cluster, managed by Ansible

## Code Example

$ansible-playbook server_deploy.yml

## Installation

 Requires ansible 2.2 and the servers to be predeployed, ssh keys set up, python and apt-python installed.

## Tests

$ansible-playbook server_deploy.yml --check should return specifics about the steps, provided that the hosts are available and correctly set up in /etc/ansible/hosts 

## Contributors

jeff.sutch@acm.org

## License
Ansible is licensed under GNU General Public License version 3.
Consul is licensed under Mozilla Public License 2.0

These code samples are licensed under Attribution-ShareAlike 3.0 United States (CC BY-SA 3.0 US)

