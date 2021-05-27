# ansible-sysmon
Playbook Description
=========

Deploys or uninstalls/upgrades Sysmon.  Also updates Sysmon configuration if the configuration file has changed.

Requirements
------------

Assumes Sysmon and sysmon configuration file is already downloaded and stored from a location on the Ansible controller.  Could be updated to download from MS or other internal location if that is an option.

Role Variables
--------------

Hostvars for authentication to Windows hosts via WinRM are stored in Ansible vault.

    ansible_password: "{{ vault_ansible_password }}"
    sysmon_version: "13.20"

Dependencies
------------

None.

License
-------

MIT

Author Information
------------------

Thomas Connelly
