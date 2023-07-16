Zucchini Universe
=========

Zucchini Universe - Base System

Role Variables
--------------

All variables are set in defaults/main.yml:

sshd:
users:
ssh_keys:
sudoers:
add_packages:
remove_packages:
rsyslog_defaults_global:
rsyslog_defaults_main_queue:
rsyslog_extra_conf:
rsyslog_action_default_template:
rsyslog_input_modules:
rsyslog_rulesets_actions:
rsyslog_rulesets:
rsyslog_rulesets_inputs:

Dependencies
------------

None.

Example Playbook
----------------

This role should be used for all Zucchini Universe systems:

    - hosts: all
      roles:
         - zucchini-base

Author Information
------------------

(c) Zucchini Universe: [www.zucchiniuniverse.org](https://www.zucchiniuniverse.org)