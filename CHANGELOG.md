# Ansible Role for Node.js

## 2.1.0 - TBC

### Major Changes

  - CI with ansible-lint and galaxy-lint-rules
  - Use shell only when shell functionality is required
  - Replace tests from Docker to LXD
  - Default install Node.js 10.x on Ubuntu 16.04 and CentOS 6
  - Default install Node.js 11.x on Ubuntu 18.04 and CentOS 7
  - Optionally override Node.js version with defaults/main.yml

## 2.0.0 - 2018-10-25

  - Ininitial release for Ansible 2.6
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 6/7
  - Install Node.js 8.x on Ubuntu 16.04 from NodeSource
  - Install Node.js 10.x on Ubuntu 18.04 from NodeSource
  - Install Node.js 8.x on CentOS 6 from NodeSource
  - Install Node.js 10.x on CentOS 7 from NodeSource
