# ac-rt88u-provider-settopbox

Added settings needed for providers, for now only kpn


# Debugging igmpproxy

/usr/sbin/igmpproxy -d -vv  /jffs/configs/igmpproxy.conf

The source address 217.166.226.234 for group 224.0.252.234, is not in any valid net for upstream VIF.

Calculated subnet online using ip 217.166.226.234 -> added to igmpproxy.conf
