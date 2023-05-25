Ansible Role Cloudflare - Zero Trust Tunnel
=========

This role installs and configures Cloudflare Zero Trust Tunnel on Ubuntu 20.04+.

Requirements
------------

Operating System Support: Ubuntu 20.04 or later

Role Variables
--------------

```
# cloudflare_tunnel_token: "base64_token"
```

Dependencies
------------

No dependency.

Example Playbook
----------------

Install
```
ansible-galaxy install cihanyilmazer.ansible_role_cloudflare
```

    - hosts: servers
      roles:
         - cihanyilmazer.ansible_role_cloudflare/tunnel

License
-------

MIT

Author Information
------------------

Cihan Yilmazer<br />
https://www.cihanyilmazer.com<br />
https://www.github.com/cihanyilmazer<br />
https://galaxy.ansible.com/cihanyilmazer<br />