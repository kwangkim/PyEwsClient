PyEwsClient
===========

Overview
--------

Microsoft Office 365 EWS (Exchange Web Services) Client Library


Usage
-----

```
usage: test.py [-h] (-s SERVER | --autodiscover) -u USERNAME -p PASSWORD
               [-a ATTACHMENT] [-l LOG_LEVEL]

PyEwsClient - Microsoft Office 365 Client Library Testing Tool

examples:
 python3 tests/test.py -u email@office365.com -p password --autodiscover -l 5
 python3 tests/test.py -u email@office365.com -p password --autodiscover \ 
                       -a tests/attach1.txt -a tests/attach2.txt -l 1 
 python3 tests/test.py --help

optional arguments:
  -h, --help            show this help message and exit
  -l LOG_LEVEL, --log-level LOG_LEVEL
                        log level (default: 0)

network connectivity arguments:
  -s SERVER, --server SERVER
                        Office 365 Server
  --autodiscover        Office 365 Autodiscovery On

authentication arguments:
  -u USERNAME, --user USERNAME
                        Office 365 Username
  -p PASSWORD, --password PASSWORD
                        Office 365 Password

email arguments:
  -a ATTACHMENT, --attachment ATTACHMENT
                        Email Attachment(s)

documentation:
 https://github.com/greenpau/PyEwsClient
```
