autondp
=======

ABOUT
-----
autondp is a NAT-like workaround for IPv6. In scenarios where ISPs just assign one IPv6 address but you want to introduce IPv6 to your NATed IPv4 subnet. autondp acts as an NDP proxy for your subnet hosts, automatically discovers and configures the route by sniffing Neighbor Solicitation packets. This is totally transparent to your neighbor hosts. autondp in written in pure C, so it's easy to port to routers and embedded devices, but it does require a kernel version of 3.8 or higher.

CREDITS
-------
Developed by [Phil Hu](http://cnphil.com). Based on works by [Alexey Andriyanov](https://github.com/andriyanov/ndp-proxy).

LICENSE
-------
autondp is Free Software under the GPL.
