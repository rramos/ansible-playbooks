# Role : collectd

Role that configures collectd service and exporter for Prometheus

# Description

The main purpose of this article is to have a step-by-step guide on how to deploy a ansible playbook to setup export metrics for a set of Linux machines using collectd and aggregating then on Prometheus.

## Requirements

1. You should have a Prometheus setup ready for this setup
2. You must be able to access the list of servers with ansible where you wont to setup this config

## How to use it ?

Just update your inventory file `hosts` and run the follwing command

```
ansible-playbook -i hosts collectd-hosts.yml --check
```


