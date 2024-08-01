

# WRCrack Tool



> WordPress Brute Force

```

usage: python WrCrack.py [options]                              
optional arguments:
  -h, --help        show this help message and exit
  -V, --version     show program's version number and exit
  -d, --debug       debugging mode

target arguments:
  -t , --target     url of the target
  -u , --username   username of the target (default: admin)
  -p , --password   password of the target (change -p to --p to use a wordlist)

  --timeout         timed out for requests
  --thread          numbers of threading multiproccesor (default: 5)
  --proxy           using a HTTP proxy (ex: http://site.com:8000)

Copyright © 2024
```

## How To Use

Using a single password
```bash
python WrCrack.py -t http://site.com/wp-login.php -u admin -p password
```

Using a multiple password / wordlist
```bash
python WrCrack.py -t http://site.com/wp-login.php -u admin --p wordlist.txt
```

## About
WrCrack is a tool used to force login into the WordPress CMS web application and is built in the Python programming language

