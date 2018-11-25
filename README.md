Ansible Jenkins Role
=========
[![Build Status](https://travis-ci.org/CastawayEGR/ansible-jenkins-role.svg?branch=master)](https://travis-ci.org/CastawayEGR/ansible-jenkins-role)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![GitHub repo size in bytes](https://img.shields.io/github/repo-size/CastawayEGR/ansible-jenkins-role.svg?logoColor=brightgreen)](https://github.com/CastawayEGR/ansible-jenkins-role)
[![GitHub last commit](https://img.shields.io/github/last-commit/CastawayEGR/ansible-jenkins-role.svg?logoColor=brightgreen)](https://github.com/CastawayEGR/ansible-jenkins-role)

Ansible role to deploy Jenkins on a CentOS 7 host.

Requirements
------------

Host that Jenkins will be deployed on is running CentOS 7.

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: jenkins
      roles:
         - ansible-jenkins-role

License
-------

MIT/BSD

Author Information
------------------

This role was created by [Michael Tipton](https://ibeta.org).
