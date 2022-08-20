# 关于git的基本操作指令：

+ 初始化：
```shell
git init
```
+ 查看状态：
```shell
git status
```
+ 开始跟踪文件(需要先保存)
```shell
git add
```
之后会处于暂存状态。
（在修改之后，又不在是储存区的文件，需要重新add
<font color='red'>任何一次修改文件之后，都需要保存和git add 来确保最新的文件处于暂存状态。</font>）

+ 对于暂存的文件如果没有疑问就可以提交，但是如果有修改就必须重新git add 所以为了方便，可以git commit -a来包括git add
```shell
git commit -a -m "zsp"
```
最后在-m之后增加修改信息，这是必要的习惯。

+ 查看历史记录
```shell
git log
```
[(<font color='red'>如果控制台出现一大堆信息与end，按q就可以退出，quit即可.</font>) ](https://blog.csdn.net/weixin_39358657/article/details/93469321) 
***
+ 连接远程仓库
查看自己有哪些仓库的权限
```shell
git remote -v
```
连接远程仓库并命名
```shell
git remote add your_name1 address
```
对于push的时候，可以控制push到哪个库的哪个分支上去
```shell
git push your_name1 branch_name
```

学会合作使用github
