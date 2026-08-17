# linux_gtfobins_sudo

Configures explicit passwordless or passworded sudo entries for selected
GTFOBins scenarios. It does not install binaries or provide exploit payloads.

## Variables

```yaml
linux_gtfobins_sudo_entries:
  - user: player
    command: /usr/bin/find
    nopasswd: true
```
