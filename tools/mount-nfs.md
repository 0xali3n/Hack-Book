---
description: >-
  The mount command in Linux attaches a device's filesystem to the Linux
  filesystem
---

# Mount nfs

```bash
showmount -e $ip
```

* To list all file sharing on that IP address

```bash
mount -t nfs $ip:/$file_path/ /$where_to_save/
```

* Get files from that nfs file share and save them to the specified location.
