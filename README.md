# Virtualized Gitlab Runner in Vagrant

Gitlab CI runner using Docker in Vagrant. Provisioned by Ansible.

## Install

```
url=https://gitlab.com/ci token=<your_token> name=<runner_name> vagrant up
```

To add another runner, you can run provisioning again

```
url=https://gitlab.com/ci token=<your_token> name=<runner_name> vagrant provision
```
