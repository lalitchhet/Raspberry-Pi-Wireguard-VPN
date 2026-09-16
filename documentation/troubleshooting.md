# Troubleshooting

## PiVPN Diagnostics

The primary diagnostic command used in the project was:

```bash
pivpn -d
```

The command provides diagnostic information that can be used to identify VPN configuration and connectivity issues. 

## Client Troubleshooting

Troubleshooting included verifying:

- WireGuard client configuration
- Client profile selection
- Network connectivity
- Router port forwarding
- WireGuard service configuration

## General Troubleshooting Process

- Verify the Raspberry Pi is reachable
- Verify the WireGuard configuration
- Verify the router port-forwarding rule
- Verify the client profile
- Run PiVPN diagnostics
- Retest the VPN connection 
