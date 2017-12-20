- 显示过滤文件
```
ls -ltr *php 
```
- 搜索文件内容
```
find ./ -type f -name "*.php" | xargs grep "function redirect" 
```
- 批量查找替换
```
mac下 sed -i '' "s/preg_replace_callback_callback/preg_replace_callback/g" `grep "preg_replace" -rl ./iwen_admin`
```
