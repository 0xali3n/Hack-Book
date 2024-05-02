---
description: get the details of hash
---

# HASHCAT

```bash
hash-identifier  # Tells which type of Hash

hashid -m 'asd' or <file>  # Tells hash Module to use

hashcat -m 0 hashes.txt /usr/share/wordlists/rockyou.txt # Cracking
```



### For Windows;

```bash
hashcat.exe -m <module_number> -a 0 <hash_file> <wordlist_file>
```
