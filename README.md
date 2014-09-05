ferm-lua
========

Ferm-lua is a tool to manage linux firewall rules.
It's like a fork of the ferm - http://ferm.foo-projects.org/
That is made in perl.

Goal
-----

Feature list :
- like ferm, support the same config file format
- remove (or just do not implement) the remote stuff
- add a way to save/restore some rules/chain without dropping everything
- add a way to support arbitrary iptables option
- like ferm, support ip[6]tables (slow) and ip[6]tables-restore format
- (missing in ferm), be able to restore counters (see: man iptables --set-counters and man iptables-save -c)
- unlike ferm, allow to put code inside the config file

