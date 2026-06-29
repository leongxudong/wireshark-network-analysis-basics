# DNS Analysis

This page documents basic DNS query and response analysis in Wireshark.

## Useful Filter

```text
dns
```

## What to Observe

| Field | Meaning |
|---|---|
| Query name | Domain name being resolved |
| Query type | Record type, such as A, AAAA, CNAME, or TXT |
| Response code | Whether the query succeeded or failed |
| Answers | Returned IP address or record value |
| Timing | Time between query and response |

## Basic Questions

- Which domains are being queried?
- Are there failed queries?
- Are responses coming from the expected DNS resolver?
- Are there repeated queries for the same domain?
- Are unusual record types present?

## Screenshot Placeholder

Add screenshot later:

```text
screenshots/wireshark-dns-query-response.png
```
