```
strace -f -v -s 4096 -yy -tt -T  -e trace='!futex' cosmic-settings
```
