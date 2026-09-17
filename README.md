# 802 Tagging Model

YANG data models and example instance data for IEEE P802.1EH Telemetry
Tagging of Data Frames (CSIG) — the link-layer operations used to carry,
compute, and update in-band congestion-signaling telemetry tags at end
stations and bridges.

## Contents

| File | Description |
|------|-------------|
| `ieee802-dot1eh-tagging.yang` | Main YANG module for P802.1EH CSIG telemetry tagging (configuration and status). |
| `ieee802-ethertype.yang` | YANG module defining IEEE 802 EtherType values. |
| `ieee802-types.yang` | YANG module with common IEEE 802 data types. |
| `ieee802-dot1eh-tagging-example.xml` | Example instance data (XML) for the `ieee802-dot1eh-tagging` module. |
| `ieee802-dot1eh-tagging-example.json` | Example instance data (JSON) for the `ieee802-dot1eh-tagging` module. |

## Namespace

```
urn:ieee:std:802.1EH:yang:ieee802-dot1eh-tagging   (prefix: ieee802-dot1eh-tagging)
```

## References

- IEEE 802.1 Working Group: http://ieee802.org/1/
- IETF RFC 8343 — A YANG Data Model for Interface Management
- IETF RFC 6991 — Common YANG Data Types

## Notes

PDF and TXT source/reference documents are excluded from version control
via `.gitignore`.
