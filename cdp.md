## Cisco discovey protocol (CDP) is used for finding out the connected Routers,Switches and their interfaces. It's Cisco proprietary protocol,so it only works on Cisco devices.

  `#show cdp neighbors` - shows interfaces,devices,holdtime\
  `#show cdp neighbors detail` - used to find out IP addresses + same as cdp neighbor 

  To disable cdp for security purposes(on a WAN interface) or when using LLDP type:

  `(config)#no cdp run` - disables cdp globally\
  `(config-if)#no cdp enable` - disables on an interface (needed to be for ex. 'interface g0/0'
