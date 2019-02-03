##  Linux常用命令
1. 查看日志
```linux
tail -f catalina.out
```
2. 统计字符串在日志出现的次数
```linux
grep "xxx" mall.log | wc -l
```
3. 统计多个字符串在日志出现的次数(每个之间加 \\|)
```linux
grep "xxx\|xxx\|xxx" mall.log | wc -l
```
4. 从10000行开始查看日志
```linux
more +10000 mall.log
```