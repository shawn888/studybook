- 显示过滤文件
```
ls -ltr *php 
```
- 搜索文件内容
```
find ./ -type f -name "*.php" | xargs grep "function redirect" 
```
- 查看tcp三次握手情况
```
netstat -antp
```
- 查看tcp发送包统计信息
```
 ss -s
```
- 查看前端机到域名的dns解析地址
```
  nslookup www.baidu.com
```x