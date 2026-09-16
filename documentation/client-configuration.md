# Client Configuration

## iPhone

The WireGuard application was installed on the iPhone.

A client configuration QR code was generated on the Raspberry Pi using:

```bash
pivpn -qr
```

## Windows

The WireGuard client was installed on Windows system.
The generated WireGuard configuration file was transferred from the Raspberry Pi using WinSCP

WinSCP was configured to use:

```text
Protocol: SCP
Port: 22
```
The configuration file was retrieved from the Pi and imported into the windows WireGuard client. 
