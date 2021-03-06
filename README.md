# FOFA 搜索工具 Python 版
# FOFA Search Tools | Version Python 

# 工具仅作为学习交流使用
# The tool is only used for learning communication ;)

Install:

```
.../FOFA_Search_Tools/>pip install requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

Help:

```
> python .\FOFA_API.py -h
Usage: FOFA_API.py By 98k
FOFA_API.py -e/--email <email> -k/--key <key> -p/--page <page> -q/--query <str>

Options:
  -h, --help                  show this help message and exit
  -e EMAIL, --email=EMAIL     target email
  -k KEY, --key=KEY           target key
  -p PAGE, --page=PAGE        target page number
  -q QUERY, --query=QUERY     target query
```

```
>python .\FOFA_SPIDER.py -h
Usage: FOFA_SPIDER.py By 98k
FOFA_SPIDER.py -n/--num <number> -c/--cookie <cookie> -p/--page <page> -q/--query <str>

Options:
  -h, --help                  show this help message and exit
  -n NUMBER, --num=NUMBER     target number,number is retry count
  -c COOKIE, --cookie=COOKIE  target cookie
  -p PAGE, --page=PAGE        target page number
  -q QUERY, --query=QUERY     target query
```

Example：

```
> python .\FOFA_API.py -e jin_guanzhang@bilibili.com -k 89c01__________________4fb7b -p 1 -q "test"
181.168.214.110:8081
confluence.isaqb.org
webmail.financecheats.com
https://133.242.201.212:2087
192.185.63.135:2086
https://185.248.199.158:2083
178.33.46.83
185.3.104.153
190.245.172.3:8081
https://132.148.236.255:2083
......
```

```
> python .\FOFA_SPIDER.py -n 3 -c "________________" -p 100 -q "test"
181.168.214.110:8081
confluence.isaqb.org
webmail.financecheats.com
https://133.242.201.212:2087
192.185.63.135:2086
https://185.248.199.158:2083
178.33.46.83
185.3.104.153
190.245.172.3:8081
https://132.148.236.255:2083
```
