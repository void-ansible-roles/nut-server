nut-server
==========


What is does this role do?
--------------------------

This role installs and configured a NUT Server.

Meta
----

Files Managed:
  * /etc/ups/ups.conf
  * /etc/ups/nut.conf
  * /etc/ups/upsd.users
  * /etc/ups/upsd.conf
  * /etc/iptables.d/upsd.rules

Defaults Provided:
  * None

Variables Required:
  * connected_UPS
    - name: Name of the connected UPS
    - driver: driver to use for the UPS
    - port: what port the ups is connected to
    - serial: serial number for the UPS
  * nut_monitor_password: password to query the NUT server

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None
