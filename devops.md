## Linux

### [vi](https://www.guru99.com/the-vi-editor.html)
```
i
:wq
:q
:q!
```

### Bash

Fork
* Fork for almost all commands
* No fork for some - cd, source etc.

> Bashrc
```
.bashrc is a shell script that Bash runs whenever it is started interactively
```

Process
```
ps aux | grep python
htop -d 1
kill -9 ...
pm2 status
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
command >out 2>&1
```

Network
```
netstat
ifconfig
curl
wget
lsof -i:8080
```

[Scheduler](https://crontab.guru/)
```
crontab * * * * * command(s)
```

## nginx
```
sudo service nginx restart
```
