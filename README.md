The actual size of the log files is 2.6 GB. Since this is too large for GitHub, I have only included a 200 MB portion.
```
strace -f -v -s 4096 -yy -tt -T  -e trace='!futex' cosmic-settings
```
