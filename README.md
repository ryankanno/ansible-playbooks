# ansible-playbooks

[![Build Status](https://travis-ci.org/ryankanno/ansible-playbooks.png?branch=master)](https://travis-ci.org/ryankanno/ansible-playbooks)

## setup

  * create `digital_ocean.ini` in the inventory directory. use [inventory/digital_ocean.ini.example](https://github.com/ryankanno/ansible-playbooks/blob/master/inventory/digital_ocean.ini.example)
  * create `droplets.yml` vars file in vars directory. use [vars/droplets.yml.example](https://github.com/ryankanno/ansible-playbooks/blob/master/vars/droplets.yml.example)
  * run export $(inventory/digital_ocean.py --env) && ansible-playbook digital_ocean/ubuntu-13.04:docker:digital_ocean.yml


