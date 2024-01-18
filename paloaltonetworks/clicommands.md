# Basic Configuration


## Management Interface IP

```
admin@fw# set deviceconfig system type static

```

```
admin@fw# set deviceconfig system ip-address <ip address> netmask <netmask> default-gateway <default gateway> dns-setting servers primary <DNS ip address>

```

```
commit
```


```
admin@fw> show interface management

-------------------------------------------------------------------------------
Name: Management Interface
Link status:
  Runtime link speed/duplex/state: 10000/full/up
  Configured link speed/duplex/state: auto/auto/auto
MAC address:
  Port MAC address 00:50:56:81:ad:e6

Ip address: 10.46.196.118
Netmask: 255.255.255.192
Default gateway: 10.46.196.65
Ipv6 address: unknown
Ipv6 link local address: fe80::250:56ff:fe81:ade6/64
Ipv6 default gateway:
-------------------------------------------------------------------------------

```
