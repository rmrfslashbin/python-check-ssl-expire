# python-check-ssl-expire
Returns the number of days till an SSL cert expires

## Use

### Basic check
This script expects one param and returns a int of days-to-expire.
```./check --host example.com```

### check-notify
Use this script to check the cert and send a pushover message if the cert will expire in x days. See script to set days-to-expire.
```./check-notify example.com```
- This script depends on https://github.com/rmrfslashbin/python-pushover

