# Wireshark Display Filters

This page records basic Wireshark display filters for network analysis.

## Common Filters

| Filter | Purpose |
|---|---|
| `tcp` | Show TCP traffic |
| `udp` | Show UDP traffic |
| `dns` | Show DNS traffic |
| `http` | Show HTTP traffic |
| `tls` | Show TLS traffic |
| `ip.addr == 192.168.1.10` | Show traffic to or from a specific IP address |
| `tcp.port == 443` | Show traffic involving TCP port 443 |
| `tcp.flags.syn == 1` | Show packets with SYN flag set |
| `tcp.analysis.retransmission` | Show TCP retransmissions |

## Analysis Notes

- Display filters do not remove packets from the capture; they only change what is shown.
- Start broad, then narrow by protocol, host, or port.
- Use packet details and stream reconstruction carefully.
- Avoid publishing packet captures that contain sensitive data.

## Screenshot Placeholder

Add screenshot later:

```text
screenshots/wireshark-useful-display-filters.png
```
