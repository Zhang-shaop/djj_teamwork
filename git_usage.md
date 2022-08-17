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
