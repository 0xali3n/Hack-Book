# Full TTYs

#### Python

{% code overflow="wrap" %}
```bash
python3 -c 'import pty; pty.spawn("/bin/bash")'
ctrl + z #Now, background it
stty raw -echo && fg # On attacker machine
export TERM=xterm-256-color # set terminal environment
```
{% endcode %}

Bash

```bash
script /dev/null -c bash
```

