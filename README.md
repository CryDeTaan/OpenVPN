# OpenVPN

This contains information on how I setup a OpenVPN connection

### Provider 
ProXPN: https://www.proxpn.com

### Setup

` ➜  ~ git clone https://github.com/CryDeTaan/OpenVPN.git  /tmp/OpenVPN/ &&  mv /tmp/OpenVPN/* /etc/openvpn && rm -r /tmp/OpennVPN`

### Configure

I use a credentials file, I am okay with this, there isn't a better way that I know of.

` ➜  ~ vim /etc/openvpn/creds `

### Startup
` ➜  ~ reboot`

Until I can find a better way.


### Auto-Start

By default, all configured VPNs are started during system boot. Edit `/etc/default/openvpn` to start specific VPNs

