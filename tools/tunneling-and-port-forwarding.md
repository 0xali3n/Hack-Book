# Tunneling and Port Forwarding

SSH graphical connection (X)

```bash
ssh -Y -C <user>@<ip> #-Y is less secure but faster than -X
```

**Tunneling localhost**

```bash
ssh -L 1234:localhost:<port> <user@target>
```
