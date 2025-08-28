# systemd-networkd-question
Configuration files providing context for a question about systemd-networkd.

In the `old` folder, the prior configuration using `ifupdown` and `radvd` resulted in clients obtaining an address via DHCPv6.

In the `new` folder, the new configuration using `systemd-networkd` results in clients never using DHCPv6 to obtain an address.
