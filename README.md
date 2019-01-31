# php-fpm-status
a cli tool to access php-fpm and show status

###useage:

1.add `pm.status_path = /status` to php-fpm.conf

2.reload/restart php-fpm program

3.`python3 php-fpm-status.py`
### then well show like this:
```
pool:                 www
process manager:      static
start time:           26/Jan/2019:14:48:34 +0800
start since:          418514
accepted conn:        3280683
listen queue:         0
max listen queue:     0
listen queue len:     0
idle processes:       995
active processes:     5
total processes:      1000
max active processes: 802
max children reached: 0
slow requests:        521
```
