Commands:

```
$ go get github.com/mtojek/packet-manipulation/pt1
$ sudo pt1
```

Output:

```
someone pinged me!!
----------
PACKET: 60 bytes, wire length 60 cap length 60 @ 2018-11-14 23:58:15.63294 +0100 CET
- Layer 1 (14 bytes) = Ethernet	{Contents=[..14..] Payload=[..46..] SrcMAC=44:33:40:11:da:47 DstMAC=1c:25:d3:e9:a1:33 EthernetType=IPv4 Length=0}
- Layer 2 (20 bytes) = IPv4	{Contents=[..20..] Payload=[..26..] Version=4 IHL=5 TOS=0 Length=46 Id=65516 Flags= FragOffset=0 TTL=64 Protocol=ICMPv4 Checksum=63878 SrcIP=192.168.0.1 DstIP=192.168.0.10 Options=[] Padding=[]}
- Layer 3 (08 bytes) = ICMPv4	{Contents=[..8..] Payload=[..18..] TypeCode=EchoRequest Checksum=52299 Id=48205 Seq=0}
- Layer 4 (18 bytes) = Payload	18 byte(s)

someone pinged me!!
----------
PACKET: 60 bytes, wire length 60 cap length 60 @ 2018-11-14 23:58:16.657603 +0100 CET
- Layer 1 (14 bytes) = Ethernet	{Contents=[..14..] Payload=[..46..] SrcMAC=44:33:40:11:da:47 DstMAC=1c:25:d3:e9:a1:33 EthernetType=IPv4 Length=0}
- Layer 2 (20 bytes) = IPv4	{Contents=[..20..] Payload=[..26..] Version=4 IHL=5 TOS=0 Length=46 Id=286 Flags= FragOffset=0 TTL=64 Protocol=ICMPv4 Checksum=63573 SrcIP=192.168.0.1 DstIP=192.168.0.10 Options=[] Padding=[]}
- Layer 3 (08 bytes) = ICMPv4	{Contents=[..8..] Payload=[..18..] TypeCode=EchoRequest Checksum=52298 Id=48205 Seq=1}
- Layer 4 (18 bytes) = Payload	18 byte(s)

someone pinged me!!
----------
PACKET: 60 bytes, wire length 60 cap length 60 @ 2018-11-14 23:58:17.672989 +0100 CET
- Layer 1 (14 bytes) = Ethernet	{Contents=[..14..] Payload=[..46..] SrcMAC=44:33:40:11:da:47 DstMAC=1c:25:d3:e9:a1:33 EthernetType=IPv4 Length=0}
- Layer 2 (20 bytes) = IPv4	{Contents=[..20..] Payload=[..26..] Version=4 IHL=5 TOS=0 Length=46 Id=295 Flags= FragOffset=0 TTL=64 Protocol=ICMPv4 Checksum=63564 SrcIP=192.168.0.1 DstIP=192.168.0.10 Options=[] Padding=[]}
- Layer 3 (08 bytes) = ICMPv4	{Contents=[..8..] Payload=[..18..] TypeCode=EchoRequest Checksum=52297 Id=48205 Seq=2}
- Layer 4 (18 bytes) = Payload	18 byte(s)
```