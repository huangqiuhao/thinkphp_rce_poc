# Introduction:
近日，thinkphp团队发布了版本更新，其中修复了一处远程代码执行漏洞，可直接getshell，影响范围：v5.x < 5.1.31，<= 5.0.23
# Dependencies:
pip -r install requirements.txt
# Usage:
```
python thinkphp_rce_poc.py 
[-] Usage: thinkphp_rce_poc.py -u http://www.targeturl.com
[!] Error: argument -u/--url is required
```
# Screenshot:
![avatar](https://github.com/heroanswer/thinkphp_rce_poc/blob/master/screenshot.jpg)
