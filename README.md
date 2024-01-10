# fclones

Install and configure [fclones](https://github.com/pkolaczk/fclones) - an
efficient duplicate file finder written in Rust.

|GitHub|Downloads|Version|
|------|---------|-------|
|[![github](https://github.com/balling-dev/ansible-role-fclones/workflows/Continuous%20Integration/badge.svg)](https://github.com/balling-dev/ansible-role-fclones/actions)|[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/balling-dev/fclones)|[![Version](https://img.shields.io/github/release/balling-dev/ansible-role-fclones.svg)](https://github.com/balling-dev/ansible-role-fclones/releases/)|

## Example Playbook

This example is taken from
[`molecule/default/converge.yml`](
https://github.com/balling-dev/ansible-role-fclones/blob/main/molecule/default/converge.yml)
and is tested on each push, pull request and release.

```yaml
---
- name: "Converge"
  hosts: "all"
  become: true
  gather_facts: true

  roles:
    - role: "balling_dev.fclones"
```

## Role Variables

The default values for the variables are set in
[`defaults/main.yml`](https://github.com/balling-dev/ansible-role-fclones/blob/main/defaults/main.yml):

```yaml
---
# Defaults file for fclones

# Version of fclones to install. Use "latest" to install latest version.
fclones_version: "latest"
```
