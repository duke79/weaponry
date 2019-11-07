## Linux

### [vi](https://www.guru99.com/the-vi-editor.html)
```
i
:wq
:q
:q!
```

### Linux commands

Fork
* Fork for almost all commands
* No fork for some - cd, source etc.

Process
```
ps aux | grep python
htop -d 1
kill -9 ...
```

Disk
```
df -h
du -h --max-depth=1 | sort -hr
```

Text
```
grep "sample input 0" ./test/* -ir
wc
head
tail
```

Network
```
netstat
ifconfig
curl
wget
lsof -i:8080
```
