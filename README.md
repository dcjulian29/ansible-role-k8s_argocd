# Ansible Role: k8s_argocd

[![Lint](https://github.com/dcjulian29/ansible-role-k8s_argocd/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-k8s_argocd/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-k8s_argocd.svg)](https://github.com/dcjulian29/ansible-role-k8s_argocd/issues)

This an Ansible role to install ArgeCD into a kubernetes cluster.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.k8s_argocd
  src: https://github.com/dcjulian29/ansible-role-k8s_argocd.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
