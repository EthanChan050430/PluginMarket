# 举报系统
## 1.功能
玩家输入`.r`可以举报一个玩家，举报的玩家会被记录在一个文件中，管理员可以查看这个文件，查看举报的玩家。
举报次数达到一定次数的玩家会被封禁。

## 2.自定义举报达到几次后踢出
在__init__.py中修改number_of_players的值即可
```python
number_of_players = 3
```
