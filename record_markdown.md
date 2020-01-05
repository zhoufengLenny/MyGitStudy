#**MARKDOWN 学习记录**
##一、文本格式化
###1.1 字体格式
####1.1.1 GIT 的提交、修改、历史查看、协作[^1]
**1. 工作区与版本库：***工作区是一个包含.git子目录（内含版本库）的目录，通过``init``在当前目录创建版本库。*


**2. 版本提交：***版本提交依次经过工作区->暂存区->版本库，通过``add``命令确定哪些文件纳入下一次提交，以快照的形式放在暂存区，通过``status``命令可以查看下一次提交的状态，通过``commit``命令创建版本提交。*

**3. 历史查看：***``log`` 命令可用来显示提交历史,通过``--graph``,``-n``,``--oneline``,``--stat``等参数实现对版本提交历史的追溯。``diff``命令可以查看两个版本提交的不同。*

**4. 推送和拉回：***``push`` 和``pull``命令实现本地和远程版本库间的共享和协作。*



















[^1]2020.01.02 周峰