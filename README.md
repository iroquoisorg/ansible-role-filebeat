# filebeat

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-filebeat.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for filebeat

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.filebeat`

# Default settings

```
elk_server: localhost
elk_ca_cert_path: /etc/beat/ca.pem
logstash_syslog_port: 5044
filebeat_key_id: 'D88E42B4'
filebeat_log_nginx: false
filebeat_custom_paths: []
filebeat_syslog_paths:
  - /var/log/syslog
  - /var/log/auth

```
