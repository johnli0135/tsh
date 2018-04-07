# tsh

Command-line utility. Uses an [SMS gateway](https://en.wikipedia.org/wiki/SMS_gateway)
to communicate with a phone via text message, allowing you to text
shell commands to your computer.

### Requirements

- a phone, GMail account, and Python 3
- [dateparser](https://github.com/scrapinghub/dateparser) installed
- [less secure apps](https://myaccount.google.com/lesssecureapps) enabled

### Usage

Start tsh:
```
python tsh.py
```

Give away your personal information:
```
Email: address@domain
Password: hunter2 (suppressed)
Phone number (numbers only): 3141592653
Phone service: AT&T
```

tsh will text you and start listening for replies.
