# Network and Port Forwarding

## Router Configuration

The home router was configured with a port-forwarding rule for the WireGuard service.

## Port Forwarding

```text
Protocol: UDP
External Port: 51820
Internal Port: 51820
Destination: Raspberry Pi WireGuard server
```

Remote Client----UDP 51820----Internet---------Home Router|--|Port Forward---------Raspberry Pi|--|WireGuard VPN---------Home Network
