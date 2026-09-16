# WireGuard Configuration

## PiVPN

PiVPN was used to deploy and manage the WireGuard VPN configuration on the Raspberry Pi.

### VPN Port

WireGuard was configured to use:

```text
UDP 51820
```

### Client Creation
Client profiles were created with:

``` text
pivpn -a
```

### Diagnostics
PiVPN provides a diagnostic command:

```text
pivpn -d
```
### Security
Each wireguard client uses its own configuration.
Client configuration files contain private cryptographic material and are therefore excluded from the public repository. 
