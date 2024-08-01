<img src="[https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbgsg-LEnF3j_K6yrP0HyZxZe_hR4rpks8LQ&usqp=CAU](https://www.google.com/url?sa=i&url=https%3A%2F%2Fonly1autoglass.com%2FBlog%2Fentryid%2F75%2Fspider-crack-does-my-windshield-need-to-be-replaced&psig=AOvVaw0xzIrS716uWHA-IYIbiuIF&ust=1722626869201000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCKD2vqfD1IcDFQAAAAAdAAAAABAE)" align="right" width="90" height="80">

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

