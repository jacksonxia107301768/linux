##  Linux common commands 
1. View log
```linux
tail -f catalina.out
```
2. Count the number of times a string appears in the log
```linux
grep "xxx" mall.log | wc -l
```
3. Count the number of times multiple strings appear in the log (add \| between each)
```linux
grep "xxx\|xxx\|xxx" mall.log | wc -l
```
4. View the log starting at line 10000
```linux
more +10000 mall.log
```

