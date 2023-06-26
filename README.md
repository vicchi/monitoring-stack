# <img valign="middle" src="https://www.vicchi.org/assets/images/avatar.jpeg" height="64" alt="Gary Gale">&nbsp;monitoring-stack

A Docker monitoring and analytics stack based on [Uptime Kuma](https://github.com/louislam/uptime-kuma) and [Shynet](https://github.com/milesmcc/shynet); all deployable with [Ansible](https://docs.ansible.com/ansible/latest/getting_started/index.html).

## Here Be Dragons

This is a personal project and relies on my own, opinionated, setup that works for sites I maintain. It might be useful as an example of how to set up and deploy one or more web stacks with Docker and Ansible. Or not. YMMV.


## Deploy

```
ansible-playbook playbooks.yml -K
```

## To Do

* Add Gitea and GitHub actions workflows for build and deployment
* Add Ansible Vault for deployment `sudo` authentication

## Colophon and Licence

[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

This is a thing made by [Gary Gale](https://www.vicchi.org/pages/about/) and is licensed under the BSD 3 Clause licence.
