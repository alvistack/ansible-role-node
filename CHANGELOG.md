# Ansible Role for Node.js

## 2.3.0 - TBC

### Major Changes

  - Porting test to Molecule based

## 2.2.0 - 2019-01-26

### Major Changes

  - Improve variables default value handling

## 2.1.0 - 2018-12-06

### Major Changes

  - CI with yamllint, ansible-lint and ansible-playbook --syntax-check
  - CI with LXD, improve systemd support
  - Use shell only when shell functionality is required
  - Default install Node.js 10.x on Ubuntu 16.04 and CentOS 6
  - Default install Node.js 11.x on Ubuntu 18.04 and CentOS 7
  - Support override with defaults/main.yml

## 2.0.0 - 2018-10-25

  - Ininitial release for Ansible 2.6
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 6/7
  - Install Node.js 8.x on Ubuntu 16.04 from NodeSource
  - Install Node.js 10.x on Ubuntu 18.04 from NodeSource
  - Install Node.js 8.x on CentOS 6 from NodeSource
  - Install Node.js 10.x on CentOS 7 from NodeSource
