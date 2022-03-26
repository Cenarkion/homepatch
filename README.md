homepatch
=========

A simple ansible playbook to patch a couple of machines in the home network

Requirements
------------

Ansible 2.6+
Caters for RedHat, Fedora & Arch systems, includes patching and bouncing the control node (arch) so the play is never expected to close cleanly

Role Variables
--------------

Nothing exciting here.

Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
---
- hosts: both
  gather_facts: true
  become: true
  roles:
    - role: homepatch
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
