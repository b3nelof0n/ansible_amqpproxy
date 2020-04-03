Ansible AMQProxy Playbook 
========

Playbook that installs and configures AMQProxy via Ansible.

Read more:

### What is AMQProxy?
An intelligent AMQP proxy, with connection and channel pooling/reusing
https://github.com/cloudamqp/amqproxy

Maintaining Long-Lived Connections with AMQProxy:
https://www.cloudamqp.com/blog/2019-05-29-maintaining-long-lived-connections-with-AMQProxy.html

## Installation

Use Ansible to install this playbook:

    $ ansible install amqpproxy

## Supported tested systems

- generic/debian10

## Role Variables
    amqp_proxy_listen_address: 127.0.0.1
    amqp_proxy_listen_port: 5673
    amqp_proxy_upstream_host: amqp://127.0.0.1:5672