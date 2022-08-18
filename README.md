ryngach.ansible-softether-vpn
===========================
Installs [Softether vpn server & client](https://www.softether.org/)

By defaults it configures only Softether SSL-VPN protocol

Requirements
------------

OS Debian/Ubuntu

Role Variables
--------------

client: see [roles/softether-vpnclient/defaults/main.yml](roles/softether-vpnclient/defaults/main.yml)
server: see [roles/softether-vpnserver/defaults/main.yml](roles/softether-vpnserver/defaults/main.yml)

Example Playbook
----------------

client: see [softether-vpnclient.yml](softether-vpnclient.yml)
server: see [softether-vpnserver.yml](softether-vpnserver.yml)


License
-------

MIT

Author Information
------------------

Ruslan Ryngach <ruslan.ryngach@gmail.com>