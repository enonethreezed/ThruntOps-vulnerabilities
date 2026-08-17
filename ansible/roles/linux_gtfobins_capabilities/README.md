# linux_gtfobins_capabilities

Applies explicit file capabilities to existing regular files. The host must
provide `getcap` and `setcap`.

```yaml
linux_gtfobins_capabilities_entries:
  - path: /usr/bin/python3
    capability: cap_setuid+eip
```
