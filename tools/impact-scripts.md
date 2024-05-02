---
description: /opt/impacket/examples
---

# Impact Scripts

## PSEXEC.py&#x20;

Used for SMB connect and code execution

```bash
psexec.py Administrator@<IP> -p Pa$$w0rd cmd.exe
```

## MsSqlClient.py

used for connecting Microsoft Windows SQL Server

```bash
mssqlclient.py [-db volume] -windows-auth <DOMAIN>/<USERNAME>:<PASSWORD>@<IP>
```

## GetADUsers.py

used to list all the users in SMB connection

```bash
GetADUsers.py -all <DOMAIN>/<USERNAME>:<password> -dc-ip <IP>

GetUserSPNs.py active.htb/svc_tgs -dc-ip 10.10.10.100 -request -save -outputfile hash
```
