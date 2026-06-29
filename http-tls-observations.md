# HTTP and TLS Observations

This page compares what can typically be observed in HTTP and TLS traffic using Wireshark.

## HTTP

HTTP traffic may expose request details in cleartext when encryption is not used.

Useful filter:

```text
http
```

Potentially visible fields:

- Host header
- Request method
- URI path
- Response code
- User agent

## TLS

TLS encrypts application content. Wireshark can still show metadata such as session establishment and destination information.

Useful filter:

```text
tls
```

Potentially visible fields:

- TLS version
- Server Name Indication, where present
- Certificate details, where visible
- Handshake messages
- Source and destination IP addresses

## Screenshot Placeholders

Add screenshots later:

```text
screenshots/wireshark-http-request.png
screenshots/wireshark-tls-handshake.png
```
