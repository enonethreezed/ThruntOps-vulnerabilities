# linux_gtfobins_suid

Applies explicit SUID ownership and modes to existing regular files. Targets
must already be installed; the role does not install packages.

```yaml
linux_gtfobins_suid_entries:
  - path: /usr/bin/R
    mode: "4755"
```
