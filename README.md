# hostloc

`python3 /home/hostloc.py`

`wget -O /home/hostloc.py https://raw.githubusercontent.com/petcat/hostloc/main/hostloc.py`

修改175、176行的username和password

```
apt install python3-pip
pip3 install requests
pip3 install pyaes
```

### 计划任务 每天4点23分执行
```
crontab -e
23 4 * * * sleep 5;python3 /home/hostloc.py
```
