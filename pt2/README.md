Commands:

```
$ go get github.com/mtojek/packet-manipulation/pt2
$ sudo pt2
```

Output:
```
2018/11/15 00:38:32 Warn: Empty EchoRequest Received
----------
Source Address: 192.168.0.1
Destination Address: 192.168.0.10
Protocol:  ICMPv4
----------
ICMP Code:  EchoRequest
ICMP Sequence Number:  0
Payload data length 18
Payload data:  [247 246 245 244 243 242 241 240 239 238 237 236 235 234 233 232 231 230]
Payload data to string:  ??????????????????
----------

2018/11/15 00:38:33 Warn: Empty EchoRequest Received
----------
Source Address: 192.168.0.1
Destination Address: 192.168.0.10
Protocol:  ICMPv4
----------
ICMP Code:  EchoRequest
ICMP Sequence Number:  1
Payload data length 18
Payload data:  [247 246 245 244 243 242 241 240 239 238 237 236 235 234 233 232 231 230]
Payload data to string:  ??????????????????
----------

2018/11/15 00:38:34 Warn: Empty EchoRequest Received
----------
Source Address: 192.168.0.1
Destination Address: 192.168.0.10
Protocol:  ICMPv4
----------
ICMP Code:  EchoRequest
ICMP Sequence Number:  2
Payload data length 18
Payload data:  [247 246 245 244 243 242 241 240 239 238 237 236 235 234 233 232 231 230]
Payload data to string:  ??????????????????
----------
```