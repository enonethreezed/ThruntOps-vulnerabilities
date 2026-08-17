# linux_scheduled_task_write

Creates a player-writable script executed by a root cron entry or systemd
timer.

```yaml
linux_scheduled_task_write_entries:
  - name: lab-maintenance
    kind: cron
    path: /opt/lab/maintenance.sh
    writable_user: player
    content: "#!/bin/sh\n"
```
