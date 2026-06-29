# TCP Three-Way Handshake

This page documents how to identify a basic TCP three-way handshake in Wireshark.

## Sequence

| Step | Packet | Meaning |
|---:|---|---|
| 1 | SYN | Client requests to start a TCP session |
| 2 | SYN, ACK | Server acknowledges and responds |
| 3 | ACK | Client acknowledges and session is established |

## Useful Filters

```text
tcp.flags.syn == 1
```

```text
tcp.port == 443
```

## What to Observe

- Source and destination IP addresses
- Source and destination ports
- TCP flags
- Sequence and acknowledgement numbers
- Timing between packets

## Screenshot Placeholder

Add screenshot later:

```text
screenshots/wireshark-tcp-handshake.png
```
