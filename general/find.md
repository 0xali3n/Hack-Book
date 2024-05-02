# Find

```bash
find / -group bugtracker  2>/dev/null

find . -type f  #Find all inside this directory with Regular files

grep -R . #Prints all

find / -name flag.txt # finds flag file in machine

find / -user root -perm /4000 2>/dev/null  #find root acces files with SUID

find / -perm -u=s -type f 2>/dev/null  

find / 2>/dev/null | grep user.txt # search machine to get user.txt file

grep -x '.\{4\}' rockyou.txt > four_chars_rockyou.txt #Search and save 4chars

```

